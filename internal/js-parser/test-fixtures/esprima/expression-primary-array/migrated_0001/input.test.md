# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-array > migrated_0001`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-primary-array/migrated_0001/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-primary-array/migrated_0001/input.js"
		end: Object {
			column: 7
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/expression-primary-array/migrated_0001/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/expression-primary-array/migrated_0001/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSArrayExpression {
					elements: Array []
					loc: Object {
						filename: "esprima/expression-primary-array/migrated_0001/input.js"
						end: Object {
							column: 7
							line: 1
						}
						start: Object {
							column: 4
							line: 1
						}
					}
				}
				left: JSAssignmentIdentifier {
					name: "x"
					loc: Object {
						filename: "esprima/expression-primary-array/migrated_0001/input.js"
						identifierName: "x"
						end: Object {
							column: 1
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
