# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > regression > destructuring-in-function-type`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/regression/destructuring-in-function-type/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/regression/destructuring-in-function-type/input.ts"
		end: Object {
			column: 0
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		TSTypeAlias {
			id: JSBindingIdentifier {
				name: "MyType"
				loc: Object {
					filename: "typescript/regression/destructuring-in-function-type/input.ts"
					identifierName: "MyType"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
			}
			typeParameters: undefined
			loc: Object {
				filename: "typescript/regression/destructuring-in-function-type/input.ts"
				end: Object {
					column: 37
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			right: TSFunctionType {
				loc: Object {
					filename: "typescript/regression/destructuring-in-function-type/input.ts"
					end: Object {
						column: 37
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
				typeAnnotation: TSAnyKeywordTypeAnnotation {
					loc: Object {
						filename: "typescript/regression/destructuring-in-function-type/input.ts"
						end: Object {
							column: 37
							line: 1
						}
						start: Object {
							column: 34
							line: 1
						}
					}
				}
				meta: TSSignatureDeclarationMeta {
					rest: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/regression/destructuring-in-function-type/input.ts"
						end: Object {
							column: 37
							line: 1
						}
						start: Object {
							column: 14
							line: 1
						}
					}
					parameters: Array [
						JSBindingObjectPattern {
							rest: undefined
							loc: Object {
								filename: "typescript/regression/destructuring-in-function-type/input.ts"
								end: Object {
									column: 24
									line: 1
								}
								start: Object {
									column: 15
									line: 1
								}
							}
							meta: JSPatternMeta {
								optional: undefined
								loc: Object {
									filename: "typescript/regression/destructuring-in-function-type/input.ts"
									end: Object {
										column: 29
										line: 1
									}
									start: Object {
										column: 15
										line: 1
									}
								}
								typeAnnotation: TSAnyKeywordTypeAnnotation {
									loc: Object {
										filename: "typescript/regression/destructuring-in-function-type/input.ts"
										end: Object {
											column: 29
											line: 1
										}
										start: Object {
											column: 26
											line: 1
										}
									}
								}
							}
							properties: Array [
								JSBindingObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "theme"
											loc: Object {
												filename: "typescript/regression/destructuring-in-function-type/input.ts"
												identifierName: "theme"
												end: Object {
													column: 22
													line: 1
												}
												start: Object {
													column: 17
													line: 1
												}
											}
										}
										loc: Object {
											filename: "typescript/regression/destructuring-in-function-type/input.ts"
											end: Object {
												column: 22
												line: 1
											}
											start: Object {
												column: 17
												line: 1
											}
										}
									}
									value: JSBindingIdentifier {
										name: "theme"
										loc: Object {
											filename: "typescript/regression/destructuring-in-function-type/input.ts"
											identifierName: "theme"
											end: Object {
												column: 22
												line: 1
											}
											start: Object {
												column: 17
												line: 1
											}
										}
									}
									loc: Object {
										filename: "typescript/regression/destructuring-in-function-type/input.ts"
										end: Object {
											column: 22
											line: 1
										}
										start: Object {
											column: 17
											line: 1
										}
									}
								}
							]
						}
					]
				}
			}
		}
		TSTypeAlias {
			id: JSBindingIdentifier {
				name: "AnotherType"
				loc: Object {
					filename: "typescript/regression/destructuring-in-function-type/input.ts"
					identifierName: "AnotherType"
					end: Object {
						column: 16
						line: 3
					}
					start: Object {
						column: 5
						line: 3
					}
				}
			}
			typeParameters: undefined
			loc: Object {
				filename: "typescript/regression/destructuring-in-function-type/input.ts"
				end: Object {
					column: 36
					line: 3
				}
				start: Object {
					column: 0
					line: 3
				}
			}
			right: TSFunctionType {
				loc: Object {
					filename: "typescript/regression/destructuring-in-function-type/input.ts"
					end: Object {
						column: 36
						line: 3
					}
					start: Object {
						column: 19
						line: 3
					}
				}
				typeAnnotation: TSAnyKeywordTypeAnnotation {
					loc: Object {
						filename: "typescript/regression/destructuring-in-function-type/input.ts"
						end: Object {
							column: 36
							line: 3
						}
						start: Object {
							column: 33
							line: 3
						}
					}
				}
				meta: TSSignatureDeclarationMeta {
					rest: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/regression/destructuring-in-function-type/input.ts"
						end: Object {
							column: 36
							line: 3
						}
						start: Object {
							column: 19
							line: 3
						}
					}
					parameters: Array [
						JSBindingArrayPattern {
							rest: undefined
							loc: Object {
								filename: "typescript/regression/destructuring-in-function-type/input.ts"
								end: Object {
									column: 23
									line: 3
								}
								start: Object {
									column: 20
									line: 3
								}
							}
							meta: JSPatternMeta {
								optional: undefined
								loc: Object {
									filename: "typescript/regression/destructuring-in-function-type/input.ts"
									end: Object {
										column: 28
										line: 3
									}
									start: Object {
										column: 20
										line: 3
									}
								}
								typeAnnotation: TSAnyKeywordTypeAnnotation {
									loc: Object {
										filename: "typescript/regression/destructuring-in-function-type/input.ts"
										end: Object {
											column: 28
											line: 3
										}
										start: Object {
											column: 25
											line: 3
										}
									}
								}
							}
							elements: Array [
								JSBindingIdentifier {
									name: "a"
									loc: Object {
										filename: "typescript/regression/destructuring-in-function-type/input.ts"
										identifierName: "a"
										end: Object {
											column: 22
											line: 3
										}
										start: Object {
											column: 21
											line: 3
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "typescript/regression/destructuring-in-function-type/input.ts"
											end: Object {
												column: 22
												line: 3
											}
											start: Object {
												column: 21
												line: 3
											}
										}
									}
								}
							]
						}
					]
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
