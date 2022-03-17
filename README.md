


# Flash-Chat [ iOS ]

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. Used Firebase Firestore as a backend database to store and retrieve messages from the cloud. 

# Technologies
* Swift
* Xcode
* Firebase
* CLTypingLabel

# What I learned

* Integrated third party libraries in your app using Cocoapods and Swift Package Manager.
* Stored data in the cloud using Firebase Firestore.
* Query and sort the Firebase database.
* Used Firebase for user authentication, registration and login.
* Used UITableViews and set their data sources and delegates.
* Created custom views using .xib files to modify native design components.
* Embeddded View Controllers in a Navigation Controller
* How to create a constants file and use static properties to store Strings and other constants.


<p float = "left" padding = 30px>
<Img src = "https://github.com/SukhrajBirSingh/Flash-Chat-iOS13/blob/main/Screenshot/Apple%20iPhone%2011%20Pro%20Max%20Presentation-2.png?raw=true">





</p>








# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}


