# ter-homeworks-05
  
## Задание 1
  
> Вывод использлвания утилиты tFlint  
  
Ошибки найденные tflint(без дублей)  
  
debian@debian:~/netology/tempy/04/src$ docker run --rm -v "$(pwd):/tflint" ghcr.io/terraform-linters/tflint --chdir=/tflint  
4 issue(s) found:  
  
../tflint/providers.tf:3:14: Warning - Missing version constraint for provider "yandex" in `required_providers` (terraform_required_providers)  
../tflint/variables.tf:36:1: Warning - variable "vms_ssh_root_key" is declared but not used (terraform_unused_declarations)  
  
> Вывод использлвания утилиты checkov(в этой папке почему то не получается использовать, в другой папке из задания Задания 3 всё работает...)  
> Использовал утилиту tfsec с дополнительно сгенерированным файлом yaml, для проверки yacloud иначе софт не видит проблем.  
  
> В основном в файлах ошибки не нашёл только в папке demonstration1/vms  
  
<p align="center">
  <img src="ter-05_1.7.png" width="800">
</p>  
  
## Задание 2
  
> Настройка s3, помимо неё ещё есть добавление кредов, но там нет особой настройки, просто доавление ключей

<p align="center">
  <img src="ter-05_1.2.png" width="800">
</p>

> Миграция в s3

<p align="center">
  <img src="ter-05_1.3.png" width="800">
</p>

<p align="center">
  <img src="ter-05_1.4.png" width="800">
</p>

> Commit to GIT()
  
https://github.com/ufilin/ter-homeworks-04.git  
  
> Ошибка доступа к state

<p align="center">
  <img src="ter-05_1.5.png" width="800">
</p>

> Снятие блокировки с state

<p align="center">
  <img src="ter-05_1.6.png" width="800">
</p>

## Задание 3

https://github.com/ufilin/ter-homeworks-04/pull/2






