# devops-netology
modified

Будут проигнорированны:

- .terraform/ - данная директория
- *.tfstate - любой файл заканчивающийся на .tfstate
- *.tfstate.* - любой файл содержаший в середине .tfstate.
- crash.log - данный файл 
- crash.*.log - любой файл начинающийся с crash. и заканчивающийся на .log
- *.tfvars - любой файл заканчивающийся на .tfvars
- *.tfvars.json - любой файл заканчивающийся на .tfvars.json
- override.tf - данный файл 
- override.tf.json - данный файл 
- *_override.tf - любой файл заканчивающийся на _override.tf
- *_override.tf.json - любой файл заканчивающийся на _override.tf.json
- .terraform.tfstate.lock.info - данный файл 
- .terraformrc - данный файл 
- terraform.rc - данный файл 