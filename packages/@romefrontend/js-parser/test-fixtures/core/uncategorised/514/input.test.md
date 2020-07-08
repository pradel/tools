# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 514`

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
			column: 34
			index: 34
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
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 15
					index: 15
					line: 1
				}
				start: Object {
					column: 14
					index: 14
					line: 1
				}
			}
			description: Object {
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Argument <emphasis>t</emphasis> name clash in strict mode"}
				advice: Array [
					log {
						category: "info"
						text: "Defined already here"
					}
					frame {
						location: Object {
							filename: "input.js"
							identifierName: "t"
							end: Object {
								column: 15
								index: 15
								line: 1
							}
							start: Object {
								column: 14
								index: 14
								line: 1
							}
						}
					}
				]
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "a"
				loc: Object {
					filename: "input.js"
					identifierName: "a"
					end: Object {
						column: 10
						index: 10
						line: 1
					}
					start: Object {
						column: 9
						index: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 34
					index: 34
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: JSBlockStatement {
				body: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 34
						index: 34
						line: 1
					}
					start: Object {
						column: 17
						index: 17
						line: 1
					}
				}
				directives: Array [
					JSDirective {
						value: "use strict"
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 32
								index: 32
								line: 1
							}
							start: Object {
								column: 19
								index: 19
								line: 1
							}
						}
					}
				]
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 16
						index: 16
						line: 1
					}
					start: Object {
						column: 10
						index: 10
						line: 1
					}
				}
				params: Array [
					JSBindingIdentifier {
						name: "t"
						loc: Object {
							filename: "input.js"
							identifierName: "t"
							end: Object {
								column: 12
								index: 12
								line: 1
							}
							start: Object {
								column: 11
								index: 11
								line: 1
							}
						}
						meta: JSPatternMeta {
							optional: undefined
							typeAnnotation: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 12
									index: 12
									line: 1
								}
								start: Object {
									column: 11
									index: 11
									line: 1
								}
							}
						}
					}
					JSBindingIdentifier {
						name: "t"
						loc: Object {
							filename: "input.js"
							identifierName: "t"
							end: Object {
								column: 15
								index: 15
								line: 1
							}
							start: Object {
								column: 14
								index: 14
								line: 1
							}
						}
						meta: JSPatternMeta {
							optional: undefined
							typeAnnotation: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 15
									index: 15
									line: 1
								}
								start: Object {
									column: 14
									index: 14
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```

 input.js:1:14 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Argument t name clash in strict mode

  ℹ Defined already here

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```