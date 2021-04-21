

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App>django-admin startproject My_Django_App

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App>cd My_Django_App

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>py manage.pystarapp MyDjangoApp
C:\Users\bp_lorraine Motlokoa\AppData\Local\Programs\Python\Python39\python.exe: can't open file 'C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\manage.pystarapp': [Errno 2] No such file or directory

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>py manage.pystartapp MyDjangoApp
C:\Users\bp_lorraine Motlokoa\AppData\Local\Programs\Python\Python39\python.exe: can't open file 'C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\manage.pystartapp': [Errno 2] No such file or directory

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>py manage.pystartapp hello
C:\Users\bp_lorraine Motlokoa\AppData\Local\Programs\Python\Python39\python.exe: can't open file 'C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\manage.pystartapp': [Errno 2] No such file or directory

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py startapp hello

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
April 21, 2021 - 22:37:55
Django version 3.2, using settings 'My_Django_App.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[21/Apr/2021 22:39:05] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 22:39:05] "GET /static/admin/css/fonts.css HTTP/1.1" 200 423
[21/Apr/2021 22:39:05] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 200 86184
[21/Apr/2021 22:39:05] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 200 85876
[21/Apr/2021 22:39:05] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 200 85692
Not Found: /favicon.ico
[21/Apr/2021 22:39:05] "GET /favicon.ico HTTP/1.1" 404 2002
[21/Apr/2021 22:39:48] "GET /admin HTTP/1.1" 301 0
[21/Apr/2021 22:39:48] "GET /admin/ HTTP/1.1" 302 0
[21/Apr/2021 22:39:48] "GET /admin/login/?next=/admin/ HTTP/1.1" 200 2214
[21/Apr/2021 22:39:48] "GET /static/admin/css/base.css HTTP/1.1" 200 19513
[21/Apr/2021 22:39:48] "GET /static/admin/css/nav_sidebar.css HTTP/1.1" 200 2271
[21/Apr/2021 22:39:48] "GET /static/admin/css/login.css HTTP/1.1" 200 939
[21/Apr/2021 22:39:48] "GET /static/admin/css/responsive.css HTTP/1.1" 200 18545
[21/Apr/2021 22:39:48] "GET /static/admin/js/nav_sidebar.js HTTP/1.1" 200 1360

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py createsuperuser

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
Traceback (most recent call last):
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 84, in _execute
    return self.cursor.execute(sql, params)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\sqlite3\base.py", line 423, in execute
    return Database.Cursor.execute(self, query, params)
sqlite3.OperationalError: no such table: auth_user

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\manage.py", line 22, in <module>
    main()
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\manage.py", line 18, in main
    execute_from_command_line(sys.argv)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\core\management\__init__.py", line 419, in execute_from_command_line
    utility.execute()
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\core\management\__init__.py", line 413, in execute
    self.fetch_command(subcommand).run_from_argv(self.argv)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\core\management\base.py", line 354, in run_from_argv
    self.execute(*args, **cmd_options)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\contrib\auth\management\commands\createsuperuser.py", line 79, in execute
    return super().execute(*args, **options)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\core\management\base.py", line 398, in execute
    output = self.handle(*args, **options)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\contrib\auth\management\commands\createsuperuser.py", line 100, in handle
    default_username = get_default_username(database=database)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\contrib\auth\management\__init__.py", line 141, in get_default_username
    auth_app.User._default_manager.db_manager(database).get(
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\manager.py", line 85, in manager_method
    return getattr(self.get_queryset(), name)(*args, **kwargs)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\query.py", line 431, in get
    num = len(clone)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\query.py", line 262, in __len__
    self._fetch_all()
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\query.py", line 1324, in _fetch_all
    self._result_cache = list(self._iterable_class(self))
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\query.py", line 51, in __iter__
    results = compiler.execute_sql(chunked_fetch=self.chunked_fetch, chunk_size=self.chunk_size)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\models\sql\compiler.py", line 1169, in execute_sql
    cursor.execute(sql, params)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 98, in execute
    return super().execute(sql, params)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 66, in execute
    return self._execute_with_wrappers(sql, params, many=False, executor=self._execute)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 75, in _execute_with_wrappers
    return executor(sql, params, many, context)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 84, in _execute
    return self.cursor.execute(sql, params)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\utils.py", line 90, in __exit__
    raise dj_exc_value.with_traceback(traceback) from exc_value
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\utils.py", line 84, in _execute
    return self.cursor.execute(sql, params)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\db\backends\sqlite3\base.py", line 423, in execute
    return Database.Cursor.execute(self, query, params)
django.db.utils.OperationalError: no such table: auth_user

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py migrate
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying auth.0001_initial... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying contenttypes.0002_remove_content_type_name... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying sessions.0001_initial... OK

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py createsuperuser
Username (leave blank to use 'bp_lorrainemotlokoa'): Lorraine
Email address: mabu.lorraine@gmail.com
Password:
Password (again):
Superuser created successfully.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
April 21, 2021 - 22:47:03
Django version 3.2, using settings 'My_Django_App.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[21/Apr/2021 22:47:24] "GET /admin/login/?next=/admin/ HTTP/1.1" 200 2214
[21/Apr/2021 22:47:24] "GET /static/admin/css/base.css HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/css/nav_sidebar.css HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/css/login.css HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/css/responsive.css HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/js/nav_sidebar.js HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 22:47:24] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 22:48:18] "POST /admin/login/?next=/admin/ HTTP/1.1" 200 2393
[21/Apr/2021 22:48:18] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 22:48:47] "POST /admin/login/?next=/admin/ HTTP/1.1" 302 0
[21/Apr/2021 22:48:47] "GET /admin/ HTTP/1.1" 200 3329
[21/Apr/2021 22:48:47] "GET /static/admin/css/dashboard.css HTTP/1.1" 200 380
[21/Apr/2021 22:48:47] "GET /static/admin/img/icon-addlink.svg HTTP/1.1" 200 331
[21/Apr/2021 22:48:47] "GET /static/admin/img/icon-changelink.svg HTTP/1.1" 200 380
[21/Apr/2021 22:50:19] "GET /admin/auth/user/ HTTP/1.1" 200 7855
[21/Apr/2021 22:50:19] "GET /static/admin/css/base.css HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/css/nav_sidebar.css HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/css/changelists.css HTTP/1.1" 200 6874
[21/Apr/2021 22:50:19] "GET /admin/jsi18n/ HTTP/1.1" 200 3195
[21/Apr/2021 22:50:19] "GET /static/admin/js/jquery.init.js HTTP/1.1" 200 347
[21/Apr/2021 22:50:19] "GET /static/admin/js/core.js HTTP/1.1" 200 5698
[21/Apr/2021 22:50:19] "GET /static/admin/js/admin/RelatedObjectLookups.js HTTP/1.1" 200 5984
[21/Apr/2021 22:50:19] "GET /static/admin/js/actions.js HTTP/1.1" 200 6540
[21/Apr/2021 22:50:19] "GET /static/admin/css/responsive.css HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/js/urlify.js HTTP/1.1" 200 7902
[21/Apr/2021 22:50:19] "GET /static/admin/js/prepopulate.js HTTP/1.1" 200 1531
[21/Apr/2021 22:50:19] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/js/vendor/jquery/jquery.js HTTP/1.1" 200 287630
[21/Apr/2021 22:50:19] "GET /static/admin/js/nav_sidebar.js HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/js/vendor/xregexp/xregexp.js HTTP/1.1" 200 232381
[21/Apr/2021 22:50:19] "GET /static/admin/img/search.svg HTTP/1.1" 200 458
[21/Apr/2021 22:50:19] "GET /static/admin/img/icon-yes.svg HTTP/1.1" 200 436
[21/Apr/2021 22:50:19] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/img/tooltag-add.svg HTTP/1.1" 200 331
[21/Apr/2021 22:50:19] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 22:50:19] "GET /static/admin/img/sorting-icons.svg HTTP/1.1" 200 1097
[21/Apr/2021 23:02:49] "GET /admin/auth/user/ HTTP/1.1" 200 7855
[21/Apr/2021 23:02:49] "GET /static/admin/css/base.css HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/css/nav_sidebar.css HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/css/changelists.css HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /admin/jsi18n/ HTTP/1.1" 200 3195
[21/Apr/2021 23:02:49] "GET /static/admin/js/vendor/jquery/jquery.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/jquery.init.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/core.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/admin/RelatedObjectLookups.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/actions.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/urlify.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/prepopulate.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/vendor/xregexp/xregexp.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/css/responsive.css HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/js/nav_sidebar.js HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/img/search.svg HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/img/icon-yes.svg HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/img/tooltag-add.svg HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/img/sorting-icons.svg HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:02:49] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:04:29] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 23:05:53] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 23:05:55] "GET / HTTP/1.1" 200 10697
Not Found: /hello
[21/Apr/2021 23:06:21] "GET /hello HTTP/1.1" 404 1984
Not Found: /hello
[21/Apr/2021 23:07:52] "GET /hello HTTP/1.1" 404 1984
Not Found: /hello
[21/Apr/2021 23:08:05] "GET /hello HTTP/1.1" 404 1984
[21/Apr/2021 23:08:11] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 23:08:11] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 23:08:11] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:08:11] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:08:11] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:09:34] "GET / HTTP/1.1" 200 10697
Not Found: /hello
[21/Apr/2021 23:09:46] "GET /hello HTTP/1.1" 404 1984
Not Found: /hello
[21/Apr/2021 23:10:12] "GET /hello HTTP/1.1" 404 1984
Not Found: /hello
[21/Apr/2021 23:11:17] "GET /hello HTTP/1.1" 404 1984
Not Found: /hello
[21/Apr/2021 23:15:10] "GET /hello HTTP/1.1" 404 1984
[21/Apr/2021 23:15:15] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 23:15:15] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 23:15:15] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:15:15] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:15:15] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>
(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>My_Django_App\urls.py changed, reloading.
Traceback (most recent call last):
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App\My_Django_App\urls.py", line 20, in <module>
    path('admin/', admin.site.urls),
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\utils\functional.py", line 246, in inner
    self._setup()
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\contrib\admin\sites.py", line 560, in _setup
    AdminSiteClass = import_string(apps.get_app_config('admin').default_site)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\apps\registry.py", line 154, in get_app_config
    self.check_apps_ready()
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\apps\registry.py", line 135, in check_apps_ready
    settings.INSTALLED_APPS
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\conf\__init__.py", line 82, in __getattr__
    self._setup(name)
  File "C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\env\lib\site-packages\django\conf\__init__.py", line 63, in _setup
    raise ImproperlyConfigured(
django.core.exceptions.ImproperlyConfigured: Requested setting INSTALLED_APPS, but settings are not configured. You must either define the environment variable DJANGO_SETTINGS_MODULE or call settings.configure() before accessing settings.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
April 21, 2021 - 23:21:38
Django version 3.2, using settings 'My_Django_App.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[21/Apr/2021 23:21:54] "GET / HTTP/1.1" 200 10697
[21/Apr/2021 23:21:54] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[21/Apr/2021 23:21:54] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:21:54] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[21/Apr/2021 23:21:54] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>
(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py create superuser
Unknown command: 'create'. Did you mean migrate?
Type 'manage.py help' for usage.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python.py migrate
'python.py' is not recognized as an internal or external command,
operable program or batch file.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py migrate
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
  No migrations to apply.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py create superuser
Unknown command: 'create'. Did you mean migrate?
Type 'manage.py help' for usage.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py createsuperuser
Username (leave blank to use 'bp_lorrainemotlokoa'): Lorraine
Error: That username is already taken.
Username (leave blank to use 'bp_lorrainemotlokoa'): Salome
Email address: Salome@68
Error: Enter a valid email address.
Email address: mabu.lorraine@gmail.com
Password:
Password (again):
The password is too similar to the username.
Bypass password validation and create user anyway? [y/N]: Root@admin02
Password:
Password (again):
Superuser created successfully.

(env) C:\Users\bp_lorraine Motlokoa\Desktop\My_Django_App\My_Django_App>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
April 21, 2021 - 23:32:06
Django version 3.2, using settings 'My_Django_App.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[21/Apr/2021 23:32:12] "GET / HTTP/1.1" 200 10697
[22/Apr/2021 00:18:04] "GET /static/admin/css/fonts.css HTTP/1.1" 304 0
[22/Apr/2021 00:18:04] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 304 0
[22/Apr/2021 00:18:04] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 304 0
[22/Apr/2021 00:18:07] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 304 0
