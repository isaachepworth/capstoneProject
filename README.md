# capstoneProject
This project was designed for the Orchestra of Southern Utah, to fill a need that OSU has needed to expand and grow their patron base. Using Xcode I made an app that focuses on bring the information needed to the patrons, giving them access to purchasing tickets and making donations right on the app. The app is focused on bring information to the patrons in an easy to read way.  Here is a sample of the code used when dealing with the forms:

@IBAction func monthChanged(_ sender: Any) {

        let length = MonthTextField.text?.count
        let card = MonthTextField.text
        if (length! > 2){
            let index = card?.index((card?.startIndex)!, offsetBy: 2)
            MonthTextField.text = String(MonthTextField.text![..<index!])
        }
    }
In order to run the app, make sure you have Xcode 9 installed, download the zip file and decompress it, then run it in the simulator.
