# KeyboardAvoidingView
replace "if (!frame || !keyboardFrame) {" for "if (!frame || !keyboardFrame || keyboardFrame.screenY === 0) {" in KeyboardAvoidingView.js on line 82.
