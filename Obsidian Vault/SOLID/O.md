# Open Closed Principle -> module must be open to extension, but closed for changes.

## Example:
protocol Savable {}

extension Favorites: Savable {}
extension Notes: Savable {}

class SaveManager{

	private(set) var content : [Savable]  = []

	func save(_ part: Savable) {
	content.append(part)
	}
}