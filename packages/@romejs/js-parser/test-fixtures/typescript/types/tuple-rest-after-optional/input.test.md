# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > tuple-rest-after-optional`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 57
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'foo'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 12
            index: 12
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
        filename: 'input.ts'
        end: Object {
          column: 56
          index: 56
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 56
            index: 56
            line: 1
          }
          start: Object {
            column: 54
            index: 54
            line: 1
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 54
            index: 54
            line: 1
          }
          start: Object {
            column: 12
            index: 12
            line: 1
          }
        }
        rest: BindingIdentifier {
          name: 'args'
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 20
              index: 20
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
          meta: PatternMeta {
            optional: undefined
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 52
                index: 52
                line: 1
              }
              start: Object {
                column: 16
                index: 16
                line: 1
              }
            }
            typeAnnotation: TSTupleType {
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 52
                  index: 52
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
              rest: TSArrayType {
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 51
                    index: 51
                    line: 1
                  }
                  start: Object {
                    column: 43
                    index: 43
                    line: 1
                  }
                }
                elementType: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 49
                      index: 49
                      line: 1
                    }
                    start: Object {
                      column: 43
                      index: 43
                      line: 1
                    }
                  }
                }
              }
              elementTypes: Array [
                NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 29
                      index: 29
                      line: 1
                    }
                    start: Object {
                      column: 23
                      index: 23
                      line: 1
                    }
                  }
                }
                TSOptionalType {
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 38
                      index: 38
                      line: 1
                    }
                    start: Object {
                      column: 31
                      index: 31
                      line: 1
                    }
                  }
                  typeAnnotation: StringKeywordTypeAnnotation {
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 37
                        index: 37
                        line: 1
                      }
                      start: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                    }
                  }
                }
              ]
            }
          }
        }
      }
    }
  ]
}
```
