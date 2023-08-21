# These are the little things you need to remember everytime you use firebase with flutter
* Before runApp() , add these lines: WidgetsFlutterBinding.ensureInitialized(); Firebase.initializeApp(options: DefaultFirebaseOptions.currentPlatform); .
