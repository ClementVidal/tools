# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > optional-chaining > optional-tagged-template-literals`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 9
			index: 9
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Tagged Template Literals are not allowed in optionalChain"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 4
					index: 4
					line: 1
				}
				start: Object {
					column: 4
					index: 4
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 9
					index: 9
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSTaggedTemplateExpression {
				typeArguments: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 9
						index: 9
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				quasi: JSTemplateLiteral {
					expressions: Array []
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 9
							index: 9
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
					quasis: Array [
						JSTemplateElement {
							cooked: "foo"
							raw: "foo"
							tail: true
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 8
									index: 8
									line: 1
								}
								start: Object {
									column: 5
									index: 5
									line: 1
								}
							}
						}
					]
				}
				tag: JSMemberExpression {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 4
							index: 4
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
					object: JSReferenceIdentifier {
						name: "a"
						loc: Object {
							filename: "input.js"
							identifierName: "a"
							end: Object {
								column: 1
								index: 1
								line: 1
							}
							start: Object {
								column: 0
								index: 0
								line: 1
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "b"
							loc: Object {
								filename: "input.js"
								identifierName: "b"
								end: Object {
									column: 4
									index: 4
									line: 1
								}
								start: Object {
									column: 3
									index: 3
									line: 1
								}
							}
						}
						optional: true
						loc: Object {
							filename: "input.js"
							identifierName: "b"
							end: Object {
								column: 4
								index: 4
								line: 1
							}
							start: Object {
								column: 3
								index: 3
								line: 1
							}
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

 input.js:1:4 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Tagged Template Literals are not allowed in optionalChain

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```