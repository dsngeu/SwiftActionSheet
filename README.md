# SwiftActionSheet
Swift Action Sheet by using power of protocol in swift 

    class ViewController: UIViewController, ActionSheetPresentable {

    }

Now you can call by using following ways:

         showActionSheet(title: "Action Sheet", message: "Power of swift protocol", 
         options: ["type1", "type2", "type3"]) { (index, option) in
            print("\(index)=\(option)")
        }

        showMessage(message: "Hey how are you !") {
            print("closed")
        }
