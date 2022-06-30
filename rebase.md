## rebase

### **git rebase *[наименование]*** - перебазировать, коммиты вашей ветки накладываются поверх текущего состояния указанной ветки.

Есть второй вариант - команда **git merge** 


Чтобы перебазировать, используйте команду:
```bash=
git rebase
```

пример:
У нас две ветки: bugFix и  main
сдвинуть наши изменения из bugFix прямо на вершину ветки main:
git rebase main
git rebase bugFix