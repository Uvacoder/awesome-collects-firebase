<!-- badges -->
<div align="center">

<!-- title -->

# Awesome Firebase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Lint Awesome List](https://github.com/jthegedus/awesome-firebase/workflows/Lint%20Awesome%20List/badge.svg)

<!-- subtitle -->

Самый актуальный список документов, докладов, инструментов, примеров &amp; статей о [Firebase](https://firebase.google.com), которые может предложить Интернет.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- translations -->

переводы: [🇬🇧 en](README.md) · [🇷🇺 ru](README_RU.md) <!-- · [🇪🇸 es](README_ES.md) · [🇮🇩 id](README_ID.md) · [🇯🇵 ja](README_JA.md) · [🇰🇷 ko](README_KO.md) · [🇵🇹 pt](README_PT.md) · [🇨🇳 zh](README_ZH.md) -->

[Firebase](https://firebase.google.com) - это платформа для разработчиков приложений, основанная на [Google Cloud Platform](https://cloud.google.com/products), предоставляющая сервисы и кроссплатформенные SDK!

</div>

<!-- toc -->

## Содержание

- [Избранное (новые выпуски)](#избранное-новые-выпуски)
- [Официальная документация и быстрый старт](#официальная-документация-и-быстрый-старт)
- [Веб](#веб)
- [Для мобильных устройств](#для-мобильных-устройств)
- [Серверная часть (Cloud Functions, BigQuery и т.д.)](#серверная-часть-cloud-functions-bigquery-и-тд)
- [Интерфейс комадной строки и редактор](#Интерфейс-комадной-строки-и-редактор)
- [Прочее](#прочее)
- [Источники информации](#Источники-информации)

**Обозначения**: 📝 сообщения в блогах · 💡 примеры · 📖 документы · 🔌 библиотеки · 🔧 инструменты · 📹 беседы/видео

<!-- START content -->

## Избранное (новые выпуски)

- 🔧 [Remote Styles with Remote Config](https://github.com/firebaseextended/remote-styles/) - Динамическая/условная загрузка CSS, хранящихся в Remote Config. ([Launch post](https://medium.com/firebase-developers/introducing-remote-styles-conditional-css-loading-made-easy-daddbbcce050)).
- 🔌 [Firecoil](https://github.com/rosariopfernandes/firecoil) - Загрузка изображения из GCS в приложение для Android, используя библиотеку Coil.
- 🔧 [Svarog](https://github.com/dantothefuture/svarog) - Создание вспомогательных функций Cloud Firestore для проверки схемы с использованием схемы JSON.
- 🔧 [Firebase Extensions](https://firebase.google.com/products/extensions) - Firebase Extensions предоставляют расширенные функциональные возможности вашим приложениям без необходимости самостоятельно исследовать, писать или отлаживать код.
- 🔧 [Firebase App Distribution](https://firebase.google.com/products/app-distribution/) - Распространение предварительных версий вашего приложения среди доверенных тестировщиков.

## Официальная документация и быстрый старт

- 📖 [Firebase Documentation](https://firebase.google.com/docs) - Официальная документация по Firebase.
- 🔧 [Firebase Status Dashboard](https://status.firebase.google.com) - Эта страница предоставляет информацию о состоянии сервисов, которые являются частью Firebase.
- 💡 [Firebase Quickstarts](https://github.com/firebase?utf8=%E2%9C%93&q=quickstart&type=&language=) - Официальные примеры для быстрого старта с Firebase.
- 💡 [Google Codelabs | Firebase](https://codelabs.developers.google.com/?cat=Firebase) - Codelabs для разработчиков Google предоставляют практическое руководство по написанию кода.

## Веб

- 🔌 [React Fire](https://github.com/FirebaseExtended/reactfire) - Официальная библиотека Firebase React с хуками, поставщиками контекста и компонентами, облегчающими взаимодействие с Firebase.
- 🔌 [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks) - React Hooks для сервисов Firebase.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-web) - FirebaseUI - это библиотека JavaScript с открытым исходным кодом для Web, которая предоставляет простые связи пользовательского интерфейса поверх SDK Firebase для сокрытия стандартного кода и применения лучших практик.
- 🔌 [Firebase UI for React](https://github.com/firebase/firebaseui-web-react) - React обертка для firebaseUI Web.
- 🔌 [GeoFire for JavaScript](https://github.com/firebase/geofire-js) - Запросы местоположения в реальном времени с Firebase.
- 💡 [FirePad](https://github.com/FirebaseExtended/firepad) - Многопользовательский текстовый редактор на Firebase.
- 🔌 [Ember Fire](https://github.com/firebase/emberFire) - Официально поддерживаемый адаптер для использования Firebase с Ember.
- 🔌 [Firebase Dart](https://github.com/FirebaseExtended/firebase-dart) - Dart обертка для Firebase.
- 🔌 [PolymerFire](https://github.com/FirebaseExtended/polymerfire) - Polymer веб-компоненты для Firebase.
- 🔌 [VueFire](https://github.com/vuejs/vuefire) - Связывает Firebase и Vue.js.
- 🔌 [Angular Fire 2](https://github.com/angular/angularfire2) - Официальная библиотека для Firebase и Angular.
- 🔌 [Re-base](https://github.com/tylermcginnis/re-base) - Библиотека вдохновленная Relay для создания React.js + Firebase приложений.
- 🔌 [React Redux Firebase](https://github.com/prescottprue/react-redux-firebase) - Redux связи для Firebase. Содержит компонент высшего порядка для использования с React.
- 🔌 [GatsbyJS Firebase Data Source](https://www.gatsbyjs.org/packages/) - Получение ваших данных Firebase прямо на статически сгенерированные страницы с помощью Gatsby.
- 🔌 [Apollo Link Firebase](https://github.com/Canner/apollo-link-firebase) - Предоставляет локальный интерфейс GraphQL для RealtimeDB. БД синхронизируется локально с устройством, Apollo Link обеспечивает запросы в локальную БД.
- 🔌 [BuckleScript Bindings for Firebase](https://github.com/avohq/bs-firebase) - Привязки BuckleScript для Firebase для использования в проектах ReasonML.
- 💡 [Angular Firebase PWA](https://github.com/codediodeio/angular-firestarter) - Angular PWA работает на Firebase. Это может послужить основой для изучения этого стека и развертывания более сложных функций.
- 🔌 [FireSQL](https://github.com/jsayol/FireSQL) - Запросы к Firestore с использованием синтаксиса SQL. Выдает минимальное количество запросов, необходимое для получения запрашиваемых вами данных.
- 📖 [Hosting Version History](https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions) - Автоматическое удаление старых версий вашего сайта.
- 🔌 [Firestorter](https://github.com/IjzerenHein/firestorter) - Используйте Firestore в React с нулевым усилием, используя MobX (также для react-native).
- 💡 [Nextbase](https://github.com/martyan/nextbase) - Шаблоны Next.js, Redux и Firebase для разработчиков, которым нужен быстрый старт проекта.

## Для мобильных устройств

- 📖 [Firebase Flutter Documentation](https://firebase.google.com/docs/flutter/setup) - Официальная документация Firebase Flutter.
- 🔌 [NativeScript plugin Firebase](https://github.com/EddyVerbruggen/nativescript-plugin-firebase) - NativeScript плагин для Firebase.
- 🔌 [FlutterFire](https://github.com/flutter/plugins/blob/master/FlutterFire.md) - Используйте Firebase сервисы в своем кросс-платформенном [Flutter](https://flutter.io/) приложении.
- 🔌 [React Native Firebase](https://github.com/invertase/react-native-firebase) - Проверенная многофункциональная модульная реализация Firebase для React Native. Поддерживает платформы iOS и Android.
- 🔌 [React Native Firebase Cloud Messaging](https://github.com/evollu/react-native-fcm) -
  Модуль React Native для Firebase Cloud Messaging и локальных уведомлений.
- 💡 [Expo Native Firebase](https://github.com/EvanBacon/expo-native-firebase) - Native Firebase Expo приложение (iOS, Android) демо для Firestore, Notifications, Analytics, Storage, Messaging, Database.
- 💡 [Flutter Calendar App](https://github.com/mattgraham1/FlutterCalendar) -
  Новое приложение Flutter, реализующее простое мобильное приложение календаря для хранения основных событий в облачной базе данных Firebase.

### Android

- 🔌 [GeoFire for Java](https://github.com/firebase/geofire-java) - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-android) - Оптимизированные UI компоненты для Firebase.
- 🔌 [FireXtensions](https://github.com/rosariopfernandes/firextensions) - Неофициальные Kotlin расширения для Firebase Android SDK.

### iOS

- 🔌 [GeoFire for Objective-C](https://github.com/firebase/geofire-objc) - Запросы местоположения в реальном времени с Firebase.
- 🔌 [Firebase UI](https://github.com/firebase/firebaseui-ios) - iOS UI связи для Firebase.
- 💡 [MLKit - ARCore](https://github.com/FirebaseExtended/MLKit-ARCore) - Пример обнаружения объектов и обозначение их с помощью 3D-меток в дополненной реальности. Использует Firebase ML Kit, ARCore и Firebase RTDB.
- 💡 [MLKit - ARKit](https://github.com/FirebaseExtended/MLKit-ARKit) - Пример обнаружения объектов с помощью Firebase ML Kit и обозначение их 3D-метками в дополненной реальности.

## Серверная часть (Cloud Functions, BigQuery и т.д.)

- 📖 [Firebase Admin Documentation](https://firebase.google.com/docs/admin/setup) - Официальная документация Firebase Admin SDK.
- 💡 [Functions Samples](https://github.com/firebase/functions-samples) - Коллекция примеров приложений, демонстрирующих популярные варианты с использованием Cloud Functions для Firebase.
- 💡 [Express Server on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/master/functions-express) - Хостинг Express сервера на Cloud Functions.
- 📝 [GraphQL Server on Cloud Functions](https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0) - Хостинг Express сервера с промежуточным слоем GraphQL на Cloud Functions.
- 💡 [Compiled Code with Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/master/functions-w-parcel) - Скомпилируйте ваш Flow, TypeScript или ReasonML для среды выполнения Node, используя Babel, TypeScript Compiler или ParcelJS.
- 📝 [BigQuery & Google Analytics](https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1) - Как создать закрытую воронку в Google Analytics для Firebase с помощью BigQuery.
- 📹 [Official Cloud Function #Firecasts](https://www.youtube.com/watch?v=2mjfI0FYP7Y&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM) - Серия видеороликов на YouTube о понимании работы облачных функций.
- 📝 [Firebase Hosting for Cloud Run Services](https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html) - Динамический контент на основе особенностей Firebase Hosting (rewrites) и Cloud Run.
- 📝 [Scheduled (Cron) Cloud Functions for Firebase](https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html) - Firebase-native триггеры Cron для облачных функций Firebase.
- 🔌 [Integrify](https://github.com/anishkny/integrify) - Обеспечение ссылочной целостности и целостности данных в Firestore с помощью предварительно настроенных триггеров Cloud Functions.
- 🔌 [Free Product Analytics with Firebase + BigQuery + Rakam](https://rakam.io/blog/free-product-analytics-with-firebase---bigquery---rakam/) - Как выполнить поведенческий анализ и анализ сегментации данных событий Firebase через BigQuery Export и Rakam.

## Интерфейс комадной строки и редактор

- 🔧 [VSCode Firebase Explorer](https://github.com/jsayol/vscode-firebase-explorer) - Исследуйте и управляйте своими проектами Firebase.
- 🔧 [Firebase Tools](https://github.com/firebase/firebase-tools) - Инструменты командной строки Firebase.
- 🔧 [Firebase CI](https://github.com/prescottprue/firebase-ci) - Упрощенное взаимодействие с Firebase для непрерывной интеграции.
- 🔧 [VSFire](https://github.com/toba/vsfire) - Расширение VSCode для подсветки синтаксиса и дополнений кода для правил безопасности и индексов Firestore.
- 🔧 [Firebase Firestore Snippets](https://github.com/peterhdd/firebase-firestore-snippets) - Содержит фрагменты для Firebase и Firestore в редакторе VSCode.
- 🔧 [Fuego](https://github.com/sgarciac/fuego) - Клиентский интерфейс командной строки Firestore с возможностью добавить/обновить/выбрать записи с фильтрацией и разбиением на страницы.
- 🔧 [Firestore Rules Generator](https://github.com/FirebaseExtended/protobuf-rules-gen) - Официальный (но экспериментальный) генератор правил Firebase для Cloud Firestore основанный на формате Google's Protocol Buffer.
- 🔧 [Firepit](https://github.com/abehaskins/firepit) - Firepit - это автономная, портативная версия Firebase CLI, которая не имеет зависимостей (включая Node.js).
- 🔧 [Fireward](https://github.com/bijoutrouvaille/fireward) - Простой в использовании язык для правил Firestore, похожий на Firebase Bolt.

## Прочее

- 🔌 [Firestore Query Browser](https://firestore-query-browser.firebaseapp.com) - WebApp в Query, Batch- редактирование и экспорт документов с переключением приложений и пользователей.
- 🔌 [FireDrill](https://github.com/scottlepp/fire-drill) - Находите, изменяте, добавляйте, удаляйте, импортируйте, экспортиртируйте и создавайте отчеты на основе данных Firebase.
- 💡 [Unity Solutions](https://github.com/FirebaseExtended/unity-solutions) - Используйте инструменты Firebase для включения общих функций в ваши игры.
- 🔌 [Firebase AIR Native Extension](https://github.com/myflashlab/Firebase-ANE) - Коллекция Firebase ANE предоставляет вам доступ к проекту Google Firebase в ваших проектах AdobeAir, поддерживаемых как на Android, так и на iOS, со 100% идентичным ActionScript API.
- 🔌 [QtFirebase](https://github.com/Larpon/QtFirebase) - Попытка вывести Google Firebase C++ API на Qt+ QML.
- 📝 [StackBlitz to Firebase Hosting Deployments](https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879) - StackBlitz (онлайн-редактор кода) для статического развертывания Firebase Hosting.
- 🔧 [Flamelink](https://flamelink.io/) - CMS для Firebase. Поддерживает Firestore, RealtimeDatabase & Storage.
- 🔧 [Canner CMS](https://github.com/Canner/canner) - CMS для разработчиков, поддерживающих источники данных, такие как Firebase/Firestore, GraphQL и Restful API.
- 📹 [Firebase Summit 2018](https://www.youtube.com/watch?v=lN0VXVXsj9k&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R) - Все доклады Firebase Summit 2018.
- 📹 [Firebase @ Google Cloud Next '18](https://www.youtube.com/watch?v=OPj26MY16F8&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL) - Все доклады Firebase @ Google Cloud Next 2018.
- 📹 [Firebase @ Google IO '18](https://www.youtube.com/watch?v=e-8fiv-vteQ&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd) - Все доклады Firebase @ Google IO 2018.
- 📹 [#AskFirebase YouTube Playlist](https://www.youtube.com/watch?v=TSzhzR4wzSE&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA) - Официальный плейлист #AskFirebase на YouTube.
- 📝 [State of Firebase (mid 2019)](https://codeburst.io/the-state-of-firebase-mid-2019-2b002c458d70) - Cloud Next & Google I/O 2019 Обновления!
- 📹 [Firebase @ Google IO '19](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO) - Все доклады Firebase @ Google IO 2019.
- 📹 [Firebase Summit 2019](https://www.youtube.com/watch?v=YKZ6rP4kwV8&list=PLl-K7zZEsYLk2OolaVXVyYrFErctrZXSX) - Все доклады Firebase @ Firebase Summit 2019.

<!-- END content -->

## Источники информации

### Официальные

📹 [Firebase YouTube](https://www.youtube.com/user/Firebase) 📝 [Firebase блог](https://firebase.googleblog.com/) 🐦 [@firebase](https://twitter.com/firebase) 🐦 [@bestoffirebase](https://twitter.com/bestoffirebase) 👤 [Firebase Facebook](https://www.facebook.com/Firebase)

### Сообщество

- 📹 [Fireship - AngularFirebase](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA)
- 📹 ru [@firebase_ru - русскоговорящее сообщество. Дружественный Telegram-чат](https://t.me/firebase_ru)

За кем еще мы должны последовать!?

## Поддержка проекта

[Поддержка любого рода приветствуются, просто следуйте инструкциям](contributing.md)!

### Участники

[Спасибо этим участникам](https://github.com/jthegedus/awesome-firebase/graphs/contributors)!

## Лицензия

[CC0 License](license)
