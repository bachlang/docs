Контроллер страниц
####################

Официальное приложение скелета CakePHP поставляется с контроллером по умолчанию **PagesController.php**. 
Это простой и дополнительный контроллер для обслуживания статического контента. Домашняя страница, 
которую вы видите после установки, создается с помощью этого контроллера и файла вида **src/Template/Pages/home.ctp**.
Если вы создадите файл src **src/Template/Pages/about_us.ctp**, вы можете получить к нему доступ, используя URL **http://example.com/pages/about_us**.
Вы можете изменять контроллер страниц в соответствии с вашими потребностями.

Когда вы «запекаете» приложение с помощью Composer, контроллер страниц создается в вашей папке src **src/Controller/**.

.. meta::
    :title lang=ru: Контроллер страниц
    :keywords lang=ru: pages controller,default controller,cakephp,ships,php,file folder,home page
