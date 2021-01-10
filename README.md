# Session

[project]:https://github.com/mazzy-ax/Session
[license]:https://github.com/mazzy-ax/Session/blob/master/LICENSE
[ax2009]:ax2009
[ax2012]:ax2012
[ax4]:ax4

[Session][project] &ndash; это дополнительные методы для класса `Session`, написанные на X++ в [Microsoft Dynamics AX 2009][ax2009], [Microsoft Dynamics AX 2012][ax2012] и [Axapta 4.0][ax4].

Пока проект `Session` реализует только один метод `isInRoleAdmin`. Метод позволяет узнать, можно ли в текущей сессии выполнять действия, которые требуют права администратора:

* пользователь имеет права локального администратора
* и текущая сессия была "запущена как администратор" (runAsAdministrator)

## ChangeLog

* [CHANGELOG.md](CHANGELOG.md)
* <https://github.com/mazzy-ax/Session/releases>

## Помощь проекту

Буду признателен за ваши замечания, предложения и советы по проекту как в разделе [Issues](https://github.com/mazzy-ax/Session/issues), так и в виде письма на адрес <mazzy@mazzy.ru>

Мазуркин Сергей (mazzy)
