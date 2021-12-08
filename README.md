# devops-netology_2.1

# исключить файлы или дирректории, находящиеся в дирректории .terraform во всех предыдущих каталогах
**/.terraform/*

# исключить файлы с расширением .tfstate и файлы, где перед .tfstate. и после любое колличество символов 
*.tfstate
*.tfstate.*

# исключить файл crash.log находящийся в любом каталоге
crash.log

# исключить все файлы с расширением .tfvars
*.tfvars

# исключить файлы override.tf, override.tf.json и файлы, оканчивающиеся на _override.tf и _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# исключить файлы .terraformrc и terraform.rc
.terraformrc
terraform.rc

line
