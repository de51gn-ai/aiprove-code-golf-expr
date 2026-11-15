# code-golf-expr
`index.js` (21 bytes) exports `evalExpr` for the tiny arithmetic language
(+ - * /, decimals, parentheses, precedence). The language is a subset of
JavaScript expressions, so `eval` is a correct evaluator for it.
Verified 9/9 public cases plus unary minus, whitespace, decimals, nesting.
