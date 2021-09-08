# devops-netology
Education devops project.
My name is Ivan Gladyshev and this is my netology education course.

Git will ignore idea files, as well as terraform files.
Git will ignore terraform 
**/.Terraform/* files,
 as well as state files
*.tfstate
*.tfstate.*
and log output
crash.log .
The terraform global environment variable files will also be ignored.
.tfvars
Files that override some local resources will also be ignored.
override.tf
override.tf.json
*_override.tf
*_override.tf.json
the last files are excluded from the command line cli (Command Line Interface)
.terraformrc
terraform.rc
