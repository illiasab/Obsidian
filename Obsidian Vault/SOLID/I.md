## Clients should not be forced to depend upon interfaces that they do not use.

protocol UserRespond {
	func positive ()
	func negative ()
	func doubt() // this type should not be comforable to userRespond, if they doubt we should have another protocol
}
protocol UserReaction {
	func doubt()
} 

