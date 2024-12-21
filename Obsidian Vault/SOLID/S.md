# Single responsibility principle - means module should be responsible only for one task


for example 
class signup {
	func register() async -> Bool {
	
	}

	func registerWithGoogle() async -> Bool {
	
	}

## not to be 
	func authstate() - > Authstate {
	// if authenticated -> .authenticated
	// if not authenticated -> not authenticated
	}

   }

can be reduced by refactoring to AuthHandler class, and Register class.