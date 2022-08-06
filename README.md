# pushNotification

“Simulator supports simulating remote push notifications, including background content fetch notifications. In Simulator, drag and drop an APNs file onto the target simulator. The file must be a JSON file with a valid Apple Push Notification Service payload, including the “aps” key. It must also contain a top-level “Simulator Target Bundle” with a string value matching the target application‘s bundle identifier.
simctl also supports sending simulated push notifications. If the file contains “Simulator Target Bundle” the bundle identifier is not required, otherwise you must provide it as an argument (8164566):
$ xcrun simctl push <device> com.example.my-app ExamplePush.apns"


Screen Recording

https://user-images.githubusercontent.com/98053898/183263960-7e15d13f-d54a-4d77-916a-69089400b416.mp4

