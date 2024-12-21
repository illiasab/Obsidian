# **D**ependency Inversion Principle - > High-level modules should not depend upon low-level modules. Both should depend upon abstractions. Abstractions should not depend upon details. Details should depend upon abstractions.


## Modules which lies upon Level are more basic in relationship with Lower Level.
## Modules which lies Lower level  are more specific in relationship with UpperLevel.
### Example of Upper Level  -> Lamp As an idea(it shines when it's on ).
### Example of LowerLevel -> more specific like spot light or Desk Lamp etc..

#### Example of DIP

protocol Interactable {
	func on()
	 func off()
}

protocol Usable {
	func useInteraction()
}

protocol Slide: Interactable {} 
protocol touch: Interactable, Usable {}
class InteractionManager {
	private let interactable : Interactable
	private var interOn: Bool = false
	func control() {
		while interOn {
			if // true {
				interactable.on()
			} else {
				interactable.off()
			   }
		   }
	}
}


