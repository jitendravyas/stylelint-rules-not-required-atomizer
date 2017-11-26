# stylelint rules list which are not required for genenerated output by atomizer.

Rules which are not required marked as **(Not required)**

## List of rules

Here are all the rules within stylelint, grouped first [by category](../../VISION.md) and then by the [*thing*](http://apps.workflower.fi/vocabs/css/en) they apply to.

### Possible errors

#### Color

-   [`color-no-invalid-hex`](https://github.com/stylelint/stylelint/blob/master/lib/rules/color-no-invalid-hex/README.md): Disallow invalid hex colors.

#### Font family 

-   [`font-family-no-duplicate-names`](https://github.com/stylelint/stylelint/blob/master/lib/rules/font-family-no-duplicate-names/README.md): Disallow duplicate font family names.
-   [`font-family-no-missing-generic-family-keyword`](https://github.com/stylelint/stylelint/blob/master/lib/rules/font-family-no-missing-generic-family-keyword/README.md): Disallow missing generic families in lists of font family names.

#### Function

-   [`function-calc-no-unspaced-operator`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-calc-no-unspaced-operator/README.md): Disallow an unspaced operator within `calc` functions.
-   [`function-linear-gradient-no-nonstandard-direction`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-linear-gradient-no-nonstandard-direction/README.md): Disallow direction values in `linear-gradient()` calls that are not valid according to the [standard syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient#Syntax).

#### String

-   [`string-no-newline`](https://github.com/stylelint/stylelint/blob/master/lib/rules/string-no-newline/README.md): Disallow (unescaped) newlines in strings.

#### Unit

-   [`unit-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/unit-no-unknown/README.md): Disallow unknown units.

#### Property

-   [`property-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/property-no-unknown/README.md): Disallow unknown properties.

#### Keyframe declaration

-   [`keyframe-declaration-no-important`](https://github.com/stylelint/stylelint/blob/master/lib/rules/keyframe-declaration-no-important/README.md): Disallow `!important` within keyframe declarations.

#### Declaration block

-   [`declaration-block-no-duplicate-properties`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-no-duplicate-properties/README.md): Disallow duplicate properties within declaration blocks.
-   [`declaration-block-no-shorthand-property-overrides`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-no-shorthand-property-overrides/README.md): Disallow shorthand properties that override related longhand properties within declaration blocks.

#### Block

-   [`block-no-empty`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-no-empty/README.md): Disallow empty blocks.

#### Selector

-   [`selector-pseudo-class-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-class-no-unknown/README.md): Disallow unknown pseudo-class selectors.
-   [`selector-pseudo-element-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-element-no-unknown/README.md): Disallow unknown pseudo-element selectors.
-   [`selector-type-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-type-no-unknown/README.md): Disallow unknown type selectors.

#### Media feature

-   [`media-feature-name-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-name-no-unknown/README.md): Disallow unknown media feature names.

#### At-rule

-   [`at-rule-no-unknown`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-no-unknown/README.md): Disallow unknown at-rules.

#### Comment

-   [`comment-no-empty`](https://github.com/stylelint/stylelint/blob/master/lib/rules/comment-no-empty/README.md):  Disallow empty comments.

#### General / Sheet

-   [`no-descending-specificity`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-descending-specificity/README.md): Disallow selectors of lower specificity from coming after overriding selectors of higher specificity.
-   [`no-duplicate-at-import-rules`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-duplicate-at-import-rules/README.md): Disallow duplicate `@import` rules within a stylesheet.
-   [`no-duplicate-selectors`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-duplicate-selectors/README.md): Disallow duplicate selectors.
-   [`no-empty-source`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-empty-source/README.md): Disallow empty sources.
-   [`no-extra-semicolons`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-extra-semicolons/README.md): Disallow extra semicolons.
-   [`no-invalid-double-slash-comments`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-invalid-double-slash-comments/README.md): Disallow double-slash comments (`//...`) which are not supported by CSS.

### Limit language features

#### Color

-   [`color-named`](https://github.com/stylelint/stylelint/blob/master/lib/rules/color-named/README.md): Require (where possible) or disallow named colors.
-   [`color-no-hex`](https://github.com/stylelint/stylelint/blob/master/lib/rules/color-no-hex/README.md): Disallow hex colors.

#### Function

-   [`function-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-blacklist/README.md): Specify a blacklist of disallowed functions.
-   [`function-url-no-scheme-relative`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-url-no-scheme-relative/README.md): Disallow scheme-relative urls.
-   [`function-url-scheme-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-url-scheme-blacklist/README.md): Specify a blacklist of disallowed url schemes.
-   [`function-url-scheme-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-url-scheme-whitelist/README.md): Specify a whitelist of allowed url schemes.
-   [`function-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-whitelist/README.md): Specify a whitelist of allowed functions.

#### Number

-   [`number-max-precision`](https://github.com/stylelint/stylelint/blob/master/lib/rules/number-max-precision/README.md): Limit the number of decimal places allowed in numbers.

#### Time

-   [`time-min-milliseconds`](https://github.com/stylelint/stylelint/blob/master/lib/rules/time-min-milliseconds/README.md): Specify the minimum number of milliseconds for time values.

#### Unit

-   [`unit-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/unit-blacklist/README.md): Specify a blacklist of disallowed units.
-   [`unit-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/unit-whitelist/README.md): Specify a whitelist of allowed units.

#### Shorthand property

-   [`shorthand-property-no-redundant-values`](https://github.com/stylelint/stylelint/blob/master/lib/rules/shorthand-property-no-redundant-values/README.md): Disallow redundant values in shorthand properties (Autofixable).

#### Value

-   [`value-no-vendor-prefix`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-no-vendor-prefix/README.md): Disallow vendor prefixes for values.

#### Custom property

-   [`custom-property-pattern`](https://github.com/stylelint/stylelint/blob/master/lib/rules/custom-property-pattern/README.md): Specify a pattern for custom properties.

#### Property

-   [`property-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/property-blacklist/README.md): Specify a blacklist of disallowed properties.
-   [`property-no-vendor-prefix`](https://github.com/stylelint/stylelint/blob/master/lib/rules/property-no-vendor-prefix/README.md): Disallow vendor prefixes for properties.
-   [`property-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/property-whitelist/README.md): Specify a whitelist of allowed properties.

#### Declaration

-   [`declaration-block-no-redundant-longhand-properties`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-no-redundant-longhand-properties/README.md): Disallow longhand properties that can be combined into one shorthand property.
-   [`declaration-no-important`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-no-important/README.md): Disallow `!important` within declarations.
-   [`declaration-property-unit-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-property-unit-blacklist/README.md): Specify a blacklist of disallowed property and unit pairs within declarations.
-   [`declaration-property-unit-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-property-unit-whitelist/README.md): Specify a whitelist of allowed property and unit pairs within declarations.
-   [`declaration-property-value-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-property-value-blacklist/README.md): Specify a blacklist of disallowed property and value pairs within declarations.
-   [`declaration-property-value-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-property-value-whitelist/README.md): Specify a whitelist of allowed property and value pairs within declarations.

#### Declaration block

-   [`declaration-block-single-line-max-declarations`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-single-line-max-declarations/README.md): Limit the number of declaration within single line declaration blocks.

#### Selector

-   [`selector-attribute-operator-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-operator-blacklist/README.md): Specify a blacklist of disallowed attribute operators.
-   [`selector-attribute-operator-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-operator-whitelist/README.md): Specify a whitelist of allowed attribute operators.
-   [`selector-class-pattern`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-class-pattern/README.md): Specify a pattern for class selectors.
-   [`selector-id-pattern`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-id-pattern/README.md): Specify a pattern for id selectors.
-   [`selector-max-attribute`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-attribute/README.md): Limit the number of attribute selectors in a selector.
-   [`selector-max-class`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-class/README.md): Limit the number of classes in a selector.
-   [`selector-max-combinators`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-combinators/README.md): Limit the number of combinators in a selector.
-   [`selector-max-compound-selectors`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-compound-selectors/README.md): Limit the number of compound selectors in a selector.
-   [`selector-max-empty-lines`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-empty-lines/README.md): Limit the number of adjacent empty lines within selectors.
-   [`selector-max-id`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-id/README.md): Limit the number of id selectors in a selector.
-   [`selector-max-specificity`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-specificity/README.md): Limit the specificity of selectors.
-   [`selector-max-type`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-type/README.md): Limit the number of type in a selector.
-   [`selector-max-universal`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-max-universal/README.md): Limit the number of universal selectors in a selector.
-   [`selector-nested-pattern`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-nested-pattern/README.md): Specify a pattern for the selectors of rules nested within rules.
-   [`selector-no-qualifying-type`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-no-qualifying-type/README.md): Disallow qualifying a selector by type.
-   [`selector-no-vendor-prefix`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-no-vendor-prefix/README.md): Disallow vendor prefixes for selectors.
-   [`selector-pseudo-class-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-class-blacklist/README.md): Specify a blacklist of disallowed pseudo-class selectors.
-   [`selector-pseudo-class-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-class-whitelist/README.md): Specify a whitelist of allowed pseudo-class selectors.

#### Media feature

-   [`media-feature-name-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-name-blacklist/README.md): Specify a blacklist of disallowed media feature names.
-   [`media-feature-name-no-vendor-prefix`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-name-no-vendor-prefix/README.md): Disallow vendor prefixes for media feature names.
-   [`media-feature-name-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-name-whitelist/README.md): Specify a whitelist of allowed media feature names.

#### Custom media

-   [`custom-media-pattern`](https://github.com/stylelint/stylelint/blob/master/lib/rules/custom-media-pattern/README.md): Specify a pattern for custom media query names.

#### At-rule

-   [`at-rule-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-blacklist/README.md): Specify a blacklist of disallowed at-rules.
-   [`at-rule-no-vendor-prefix`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-no-vendor-prefix/README.md): Disallow vendor prefixes for at-rules.
-   [`at-rule-whitelist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-whitelist/README.md): Specify a whitelist of allowed at-rules.

#### Comment

-   [`comment-word-blacklist`](https://github.com/stylelint/stylelint/blob/master/lib/rules/comment-word-blacklist/README.md): Specify a blacklist of disallowed words within comments.

#### General / Sheet

-   [`max-nesting-depth`](https://github.com/stylelint/stylelint/blob/master/lib/rules/max-nesting-depth/README.md): Limit the depth of nesting.
-   [`no-unknown-animations`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-unknown-animations/README.md): Disallow unknown animations.

### Stylistic issues

#### Color

-   [`color-hex-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/color-hex-case/README.md): Specify lowercase or uppercase for hex colors (Autofixable).
-   [`color-hex-length`](https://github.com/stylelint/stylelint/blob/master/lib/rules/color-hex-length/README.md): Specify short or long notation for hex colors (Autofixable).

#### Font family

-   [`font-family-name-quotes`](https://github.com/stylelint/stylelint/blob/master/lib/rules/font-family-name-quotes/README.md): Specify whether or not quotation marks should be used around font family names.

#### Font weight

-   [`font-weight-notation`](https://github.com/stylelint/stylelint/blob/master/lib/rules/font-weight-notation/README.md): Require numeric or named (where possible) `font-weight` values.

#### Function

-   [`function-comma-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-comma-newline-after/README.md): Require a newline or disallow whitespace after the commas of functions.
-   [`function-comma-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-comma-newline-before/README.md): Require a newline or disallow whitespace before the commas of functions.
-   [`function-comma-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-comma-space-after/README.md): Require a single space or disallow whitespace after the commas of functions.
-   [`function-comma-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-comma-space-before/README.md): Require a single space or disallow whitespace before the commas of functions.
-   [`function-max-empty-lines`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-max-empty-lines/README.md): Limit the number of adjacent empty lines within functions.
-   [`function-name-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-name-case/README.md): Specify lowercase or uppercase for function names.
-   [`function-parentheses-newline-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-parentheses-newline-inside/README.md): Require a newline or disallow whitespace on the inside of the parentheses of functions.
-   [`function-parentheses-space-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-parentheses-space-inside/README.md): Require a single space or disallow whitespace on the inside of the parentheses of functions.
-   [`function-url-quotes`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-url-quotes/README.md): Require or disallow quotes for urls.
-   [`function-whitespace-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/function-whitespace-after/README.md): Require or disallow whitespace after functions.

#### Number

-   [`number-leading-zero`](https://github.com/stylelint/stylelint/blob/master/lib/rules/number-leading-zero/README.md): Require or disallow a leading zero for fractional numbers less than 1 (Autofixable).
-   [`number-no-trailing-zeros`](https://github.com/stylelint/stylelint/blob/master/lib/rules/number-no-trailing-zeros/README.md): Disallow trailing zeros in numbers (Autofixable).

#### String

-   [`string-quotes`](https://github.com/stylelint/stylelint/blob/master/lib/rules/string-quotes/README.md): Specify single or double quotes around strings (Autofixable).

#### Length

-   [`length-zero-no-unit`](https://github.com/stylelint/stylelint/blob/master/lib/rules/length-zero-no-unit/README.md): Disallow units for zero lengths (Autofixable).

#### Unit

-   [`unit-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/unit-case/README.md): Specify lowercase or uppercase for units.

#### Value

-   [`value-keyword-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-keyword-case/README.md): Specify lowercase or uppercase for keywords values.

#### Value list

-   [`value-list-comma-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-list-comma-newline-after/README.md): Require a newline or disallow whitespace after the commas of value lists.
-   [`value-list-comma-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-list-comma-newline-before/README.md): Require a newline or disallow whitespace before the commas of value lists.
-   [`value-list-comma-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-list-comma-space-after/README.md): Require a single space or disallow whitespace after the commas of value lists.
-   [`value-list-comma-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-list-comma-space-before/README.md): Require a single space or disallow whitespace before the commas of value lists.
-   [`value-list-max-empty-lines`](https://github.com/stylelint/stylelint/blob/master/lib/rules/value-list-max-empty-lines/README.md): Limit the number of adjacent empty lines within value lists.

#### Custom property

-   [`custom-property-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/custom-property-empty-line-before/README.md): Require or disallow an empty line before custom properties (Autofixable).

#### Property

-   [`property-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/property-case/README.md): Specify lowercase or uppercase for properties.

#### Declaration

-   [`declaration-bang-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-bang-space-after/README.md): Require a single space or disallow whitespace after the bang of declarations.
-   [`declaration-bang-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-bang-space-before/README.md): Require a single space or disallow whitespace before the bang of declarations.
-   [`declaration-colon-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-colon-newline-after/README.md): Require a newline or disallow whitespace after the colon of declarations.
-   [`declaration-colon-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-colon-space-after/README.md): Require a single space or disallow whitespace after the colon of declarations.
-   [`declaration-colon-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-colon-space-before/README.md): Require a single space or disallow whitespace before the colon of declarations.
-   [`declaration-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-empty-line-before/README.md): Require or disallow an empty line before declarations (Autofixable).

#### Declaration block

-   [`declaration-block-semicolon-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-semicolon-newline-after/README.md): Require a newline or disallow whitespace after the semicolons of declaration blocks.
-   [`declaration-block-semicolon-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-semicolon-newline-before/README.md): Require a newline or disallow whitespace before the semicolons of declaration blocks.
-   [`declaration-block-semicolon-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-semicolon-space-after/README.md): Require a single space or disallow whitespace after the semicolons of declaration blocks.
-   [`declaration-block-semicolon-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-semicolon-space-before/README.md): Require a single space or disallow whitespace before the semicolons of declaration blocks.
-   [`declaration-block-trailing-semicolon`](https://github.com/stylelint/stylelint/blob/master/lib/rules/declaration-block-trailing-semicolon/README.md): Require or disallow a trailing semicolon within declaration blocks.

#### Block

-   [`block-closing-brace-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-closing-brace-empty-line-before/README.md): Require or disallow an empty line before the closing brace of blocks.
-   [`block-closing-brace-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-closing-brace-newline-after/README.md): Require a newline or disallow whitespace after the closing brace of blocks.
-   [`block-closing-brace-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-closing-brace-newline-before/README.md): Require a newline or disallow whitespace before the closing brace of blocks.
-   [`block-closing-brace-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-closing-brace-space-after/README.md): Require a single space or disallow whitespace after the closing brace of blocks.
-   [`block-closing-brace-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-closing-brace-space-before/README.md): Require a single space or disallow whitespace before the closing brace of blocks.
-   [`block-opening-brace-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-opening-brace-newline-after/README.md): Require a newline after the opening brace of blocks.
-   [`block-opening-brace-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-opening-brace-newline-before/README.md): Require a newline or disallow whitespace before the opening brace of blocks.
-   [`block-opening-brace-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-opening-brace-space-after/README.md): Require a single space or disallow whitespace after the opening brace of blocks.
-   [`block-opening-brace-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/block-opening-brace-space-before/README.md): Require a single space or disallow whitespace before the opening brace of blocks.

#### Selector

-   [`selector-attribute-brackets-space-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-brackets-space-inside/README.md): Require a single space or disallow whitespace on the inside of the brackets within attribute selectors.
-   [`selector-attribute-operator-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-operator-space-after/README.md): Require a single space or disallow whitespace after operators within attribute selectors.
-   [`selector-attribute-operator-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-operator-space-before/README.md): Require a single space or disallow whitespace before operators within attribute selectors.
-   [`selector-attribute-quotes`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-attribute-quotes/README.md): Require or disallow quotes for attribute values.
-   [`selector-combinator-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-combinator-space-after/README.md): Require a single space or disallow whitespace after the combinators of selectors.
-   [`selector-combinator-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-combinator-space-before/README.md): Require a single space or disallow whitespace before the combinators of selectors.
-   [`selector-descendant-combinator-no-non-space`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-descendant-combinator-no-non-space/README.md): Disallow non-space characters for descendant combinators of selectors.
-   [`selector-pseudo-class-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-class-case/README.md): Specify lowercase or uppercase for pseudo-class selectors.
-   [`selector-pseudo-class-parentheses-space-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-class-parentheses-space-inside/README.md): Require a single space or disallow whitespace on the inside of the parentheses within pseudo-class selectors.
-   [`selector-pseudo-element-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-element-case/README.md): Specify lowercase or uppercase for pseudo-element selectors.
-   [`selector-pseudo-element-colon-notation`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-pseudo-element-colon-notation/README.md): Specify single or double colon notation for applicable pseudo-elements.
-   [`selector-type-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-type-case/README.md): Specify lowercase or uppercase for type selector.

#### Selector list

-   [`selector-list-comma-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-list-comma-newline-after/README.md): Require a newline or disallow whitespace after the commas of selector lists.
-   [`selector-list-comma-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-list-comma-newline-before/README.md): Require a newline or disallow whitespace before the commas of selector lists.
-   [`selector-list-comma-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-list-comma-space-after/README.md): Require a single space or disallow whitespace after the commas of selector lists.
-   [`selector-list-comma-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/selector-list-comma-space-before/README.md): Require a single space or disallow whitespace before the commas of selector lists.

#### Rule

-   [`rule-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/rule-empty-line-before/README.md): Require or disallow an empty line before rules (Autofixable).

#### Media feature

-   [`media-feature-colon-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-colon-space-after/README.md): Require a single space or disallow whitespace after the colon in media features.
-   [`media-feature-colon-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-colon-space-before/README.md): Require a single space or disallow whitespace before the colon in media features.
-   [`media-feature-name-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-name-case/README.md): Specify lowercase or uppercase for media feature names.
-   [`media-feature-parentheses-space-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-parentheses-space-inside/README.md): Require a single space or disallow whitespace on the inside of the parentheses within media features.
-   [`media-feature-range-operator-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-range-operator-space-after/README.md): Require a single space or disallow whitespace after the range operator in media features.
-   [`media-feature-range-operator-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-feature-range-operator-space-before/README.md): Require a single space or disallow whitespace before the range operator in media features.

#### Media query list

-   [`media-query-list-comma-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-query-list-comma-newline-after/README.md): Require a newline or disallow whitespace after the commas of media query lists.
-   [`media-query-list-comma-newline-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-query-list-comma-newline-before/README.md): Require a newline or disallow whitespace before the commas of media query lists.
-   [`media-query-list-comma-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-query-list-comma-space-after/README.md): Require a single space or disallow whitespace after the commas of media query lists.
-   [`media-query-list-comma-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/media-query-list-comma-space-before/README.md): Require a single space or disallow whitespace before the commas of media query lists.

#### At-rule

-   [`at-rule-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-empty-line-before/README.md): Require or disallow an empty line before at-rules (Autofixable).
-   [`at-rule-name-case`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-name-case/README.md): Specify lowercase or uppercase for at-rules names (Autofixable).
-   [`at-rule-name-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-name-newline-after/README.md): Require a newline after at-rule names.
-   [`at-rule-name-space-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-name-space-after/README.md): Require a single space after at-rule names.
-   [`at-rule-semicolon-newline-after`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-semicolon-newline-after/README.md): Require a newline after the semicolon of at-rules.
-   [`at-rule-semicolon-space-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/at-rule-semicolon-space-before/README.md): Require a single space or disallow whitespace before the semicolons of at rules.

#### Comment

-   [`comment-empty-line-before`](https://github.com/stylelint/stylelint/blob/master/lib/rules/comment-empty-line-before/README.md): Require or disallow an empty line before comments (Autofixable).
-   [`comment-whitespace-inside`](https://github.com/stylelint/stylelint/blob/master/lib/rules/comment-whitespace-inside/README.md): Require or disallow whitespace on the inside of comment markers.

#### General / Sheet

-   [`indentation`](https://github.com/stylelint/stylelint/blob/master/lib/rules/indentation/README.md): Specify indentation (Autofixable).
-   [`max-empty-lines`](https://github.com/stylelint/stylelint/blob/master/lib/rules/max-empty-lines/README.md): Limit the number of adjacent empty lines.
-   [`max-line-length`](https://github.com/stylelint/stylelint/blob/master/lib/rules/max-line-length/README.md): Limit the length of a line.
-   [`no-eol-whitespace`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-eol-whitespace/README.md): Disallow end-of-line whitespace.
-   [`no-missing-end-of-source-newline`](https://github.com/stylelint/stylelint/blob/master/lib/rules/no-missing-end-of-source-newline/README.md): Disallow missing end-of-source newlines (Autofixable).

