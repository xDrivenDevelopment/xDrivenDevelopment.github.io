# Начни разрабатывать правильно на 1С

### Установи GIT

```
для Windows > http://msysgit.github.io/
для RMP > yum install git-core
для DEB > apt-get install git
```

### Сделай GIT репозиторий для своего продукта на 1С

```sh
> git init ./PROJECTNAME
> cd ./PROJECTNAME
```

### Подключи стандартные каталоги

```sh
> git remote add workflow https://github.com/xUnitFor1C/xdd-bootstrap-1C.git
> git fetch workflow
> git merge workflow/master 
```

### Настрой окружение

```sh
> git submodule init
> git submodule update
> cd .\utils\precommit1c\ && copy-to-hook.cmd && cd .\..\..\..\

```

### Начни писать тесты

```sh
> copy ./tests/Test_MyFirstTest.epf ./tests/Тест_ПроверитьМир.epf
```

### Настрой сервер сборок и развертывания

[Прочитай первичное описание](
https://github.com/xDrivenDevelopment/xUnitFor1C/wiki/%D0%97%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2-%D0%B8%D0%B7-Jenkins)

**PROFFIT !!!**

----

# Для желающих развиваться и обучаться

* смотри за [новостями проектов GitHub](https://github.com/xDrivenDevelopment)

# Для желающих участовать в разработке инструментария

1. выбери задачу [на одном из проектов GitHub](https://github.com/xDrivenDevelopment)
2. сделай git fork и git pull request
3. присоединяйся к группе обсуждения [xDrivenDevelopment](https://groups.google.com/forum/#!forum/ydd-1c-community)
