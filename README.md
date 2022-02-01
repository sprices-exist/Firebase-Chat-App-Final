# Firebase-Chat-App-Final
An android real-time chat application implemented using firebase. 

Code contained in: https://github.com/sprices-exist/Firebase-Chat-App-Final/tree/main/app/src/main/java/com/google/firebase/codelab/friendlychat

![1](https://user-images.githubusercontent.com/68065642/151910389-2bf10e9d-23c8-4377-ad10-2042f9854c99.JPG)

Messaging UI


![3](https://user-images.githubusercontent.com/68065642/151910453-a8402970-7154-4031-ad2f-b409fca01a3f.JPG)

User Authentication using firebase


![4](https://user-images.githubusercontent.com/68065642/151910497-bd9e49ec-3c82-4d9b-830f-d12ceb006cf8.JPG)

AuthUI for login


![6](https://user-images.githubusercontent.com/68065642/151910791-e2f58611-cd02-4f2e-b3b6-2d797379e4ff.JPG)

Users added to firebase database after registering through AuthUI


Realtime database rules on firebase:

 {
   "rules": {
     "messages": {
       ".read": "auth.uid != null",
       ".write": "auth.uid != null"
     }
   }
 }
