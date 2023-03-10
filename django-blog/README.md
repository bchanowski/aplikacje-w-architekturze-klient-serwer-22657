# Blog Django

#### Layout strony

Na samej górze widnieje tytuł strony, a pod nim można zobaczyć dodane posty, w prawym górnym rogu znajduję się plus, który przeniesie nas do dodawania postu.

![Layout strony](/django-blog/assets/layout-strony.png "Layout strony")

#### Dodawanie postu

Po kliknięciu plusa w prawym górnym rogu, pokażę się nam ekran dodawania postów, musimy tutaj wpisać tytuł oraz opis postu, aby móc go dodać

![Dodawanie postu](/django-blog/assets/dodaj-post.png "Dodawania postu")

#### Detale postu

Po dodaniu się postu od razu zostaniemy przeniesieni do jego detali, tutaj możemy zuważyć dwa nowe przyciski - edycji (ołówek) i usunięcia (śmietnik), aby wrócić na stronę główną i zobaczyć wszytkie posty klikamy w główny nagłówek.

![Post detail](/django-blog/assets/post-detail.png "Post detail")

![Lista postów](/django-blog/assets/post-list.png "Lista postów")

Jak widać nasz post dodał się do naszej listy postów, wróćmy teraz do detali naszego nowego postu i kliknijmy przycisk edycji.

#### Edycja postów

Po kliknięciu przycisku edycji pojawi nam się tak sam ekran jak przy dodawaniu postu, tylko tym razem będzie już wypełniony, będzie jednak działał tak samo. Po kliknięciu save nasz post się edytuje.

![Edycja postu](/django-blog/assets/post-edycja.png "Edycja postu")

![Post edytowany](/django-blog/assets/post-edytowany.png "Post edytowany")

#### Usunięcie postu

Kliknijmy teraz przycisk usuwania, pojwi nam się pusty ekran strony, a po powrocie na stronę główną usunięty post nie będzie się pojawiał na naszej liście.

![Post usunięty](/django-blog/assets/post-del.png "Post usunięty")

![Layout strony](/django-blog/assets/layout-strony.png "Layout strony")

![Strona główna](/django-blog/assets/str-glw-no-user.png "Strona głowna")

Najpierw zatem zarejestrujmy użytkownika. Po rejestracji otrzymamy na maila wiadomość z linkiem do aktywacji konta.

![Rejestracja](/django-blog/assets/signup.png "Rejestracja")

![Rejestracja](/django-blog/assets/signup-done.png "Rejestracja")

![Rejestracja](/django-blog/assets/signup-activate.png "Rejestracja")

![Rejestracja](/django-blog/assets/signup-activate-done.png "Rejestracja")

Po aktywacji konta jesteśmy od razu zalogowani, wyloguję się jednak żeby pokazać działanie logowania.

![Logowanie](/django-blog/assets/login.png "Logowanie")

![Logowanie](/django-blog/assets/login-done.png "Logowanie")

Jak widać zniknęły nam opcje rejestracja, login oraz reset hasła, pojawiło się za to opcja zmiany hasła.

![Zmiana hasła](/django-blog/assets/chng-pass.png "Zmiana hasła")

![Zmiana hasła](/django-blog/assets/chng-pass-done.png "Zmiana hasła")

Spróbujmy teraz zresetować hasło, znów musimy się wylogować.

![Reset hasła](/django-blog/assets/reset-pass.png "Reset hasła")

![Reset hasła](/django-blog/assets/reset-pass-done.png "Reset hasła")

Po resecie hasła również otrzymamy maila z linkiem do resetu.

![Reset hasła](/django-blog/assets/reset-pass-mail.png "Reset hasła")

![Reset hasła](/django-blog/assets/reset-pass-mail-done.png "Reset hasła")

Nowy użytkownik może tylko wyświetlać posty, nie dodawać czy edytować.

![Logowanie](/django-blog/assets/login-auth.png "Logowanie")

## Gmail

![Logowanie gmail](/django-blog/assets/login-gmail.png "Logowanie gmail")

![Logowanie gmail](/django-blog/assets/login-gmail-done.png "Logowanie gmail")

## Discord

![Logowanie discord](/django-blog/assets/login-discord.png "Logowanie discord")

![Logowanie discord](/django-blog/assets/login-discord-done.png "Logowanie discord")
