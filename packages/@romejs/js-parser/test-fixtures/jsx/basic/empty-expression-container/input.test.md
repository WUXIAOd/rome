# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > empty-expression-container`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
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
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
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
      expression: JSXElement {
        name: JSXIdentifier {
          name: 'a'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 2
              index: 2
              line: 1
            }
            start: Object {
              column: 1
              index: 1
              line: 1
            }
          }
        }
        attributes: Array []
        selfClosing: false
        typeArguments: undefined
        loc: Object {
          filename: 'input.js'
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
        children: Array [
          JSXExpressionContainer {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 5
                index: 5
                line: 1
              }
              start: Object {
                column: 3
                index: 3
                line: 1
              }
            }
            expression: JSXEmptyExpression {
              loc: Object {
                filename: 'input.js'
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
          }
        ]
      }
    }
  ]
}
```
