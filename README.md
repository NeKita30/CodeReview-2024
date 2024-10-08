## Шаблон гитхаба для сдачи задач по курсу "Алгоритмы и структуры данных"

> Все сдаваемые задачи должны быть написаны на языке С++

> Код, выкладываемый в репозиторий, должен пройти все тесты в тестирующей системе 

### Подготовка репозитория:
1. Зарегистрируйтесь в гитхабе, если вы этого еще не сделали
2. Создайте репозиторий ([инструкция](https://docs.github.com/en/get-started/quickstart/create-a-repo)).

**Важно:** делайте репозиторий ***приватным***

3. В README.md напишите: Имя, Фамилия, номер группы
4. Добавьте семинариста (MrMarvinColex) и ассистента (NeKita30) в коллабораторы ([инструкция](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)).


### Как заливать задачи (можно все делать в веб-версии гитхаба и не клонировать репозиторий):
- создаете новую ветку с названием вида: ```1contest_taskA``` ([инструкция](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)).

**Важно:** все новые ветки создавайте из ветки ```main```
- переключаетесь на созданную ветку и в папку ```1contest``` заливаете ваше решение в файл ```taskA.cpp```. В веб-версии создание папки делается с помощью создания файла с названием через ```/```, то есть вот так: ```1contest/taskA.cpp```. На всякий случай уточню: если во 2ом контесте задачи на ревью B и С, то вам нужно будет заливать в тот же самый репозиторий, но в папочки с названием "2contest" файлы ```taskB.cpp``` и ```taskC.cpp```

**Не забывайте пожалуйста проставлять расширение файла** (чтобы была подсветка кода, встроенная в гитхаб)

### Как сдавать задачи:
После того, как вы зальете решение, создайте Merge Request на слияние вашей ветки с веткой ```main``` ([инструкция](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)). В названии MR'a напишите номер контеста и задачи, которая сдается. В комментарии к MR вставьте ссылку на соответствующую посылку вашего решения в контесте.

**Важно:** нажимать на кнопку ```Merge pull request``` ***не нужно***.

После создания реквеста, откройте его и справа в разделе reviewers добавьте NeKita30 (это необходимо, чтобы ассистент увидел, что вы сдали задачу, а не бегал по вашим репозиториям в поисках того, что можно проверить).

Потом ваша задача будет проверена. Если все хорошо, то MR будет закрыт и ваше решание окажется в ветке ```main```. Если по коду будут замечания, то они появятся в комментариях к MR-у. В обоих исходах вам на почту придет уведомление о состоянии MR (задача сдана или решение отправлено на доработку). Письмо может упасть в спам, но такого не должно произойти. Чтобы внести правки в решения, перейдите на ветку с вашей задачей и отредактируйте файл с кодом. Все изменения автоматически подтянутся в MR. После того как поправите код, вам необходимо заслать новый код в тестирующую систему и приложить ссылку на новую посылку в MR в виде комментария. Иначе задача не будет принята. Логично, что надо еще попросить ассистента о повторной проверке. Это можно сделать нажав на кнопочку re-request review внутри секции, где вы назначали Reviewer'а. После перепроверки и отсутсвия недочетов решение будет смерджено.

Визуализация того, куда жмякать для переотправки решения на ревью
![image](https://github.com/PolinaChubenko/AaDS-template/assets/70897695/5e5a4781-4d53-46aa-a89e-8668b959eac8)

Если вы продвинутый пользователь гит'а и делаете все в локальном репозитории, а не в веб-версии, то *не забывайте* делать ```git push```. 

> Учтите, что на проверку решения нужно время. Ассистент тоже человек, иногда спит / ест / ~~живет своей жизнью~~ и т.д., поэтому заливать все на гитхаб в последний момент - это очень плохая идея. 

Пример того, как будут выглядеть сданные задачи добавлен в папку ```1contest```.

> [базовые требования к коду](https://docs.google.com/document/d/1-Cpe10CgwtGOnJWHjpTmapCMTR59CGe-AfKlDOMR5fo)

> [кодстайл курса](https://docs.google.com/document/d/1HmFPnUPKfx8fXtU_rNm0lWzMwo7zr7RdCfAHbAMedjo).

:sparkles:Всем удачи!:sparkles:
