### В файле .gitignore , который находиться в папке terraform будут проигнорированый следующие файлы:

- Всё содержимое папки  .terraform/
- Все файлы с расширением .tfstate и .tfstate. и любое окончание после точки
- файлы crash.log и любые файлы которые имеют между точками любое знеачение crash.*.log
- Все файлы с расширением .tfvars и .tfvars.json
- Файлы override.tf , override.tf.json
- Файлы которые начинаються на _override.tf и _override.tf.json
- файл .terraform.tfstate.lock.info
- файлы .terraformrc и terraform.rc 