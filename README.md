# Emmet snippets
A collection of Emmet snippets for GOV.UK [elements](http://govuk-elements.herokuapp.com/).

> So far it's just HTML snippets, these might grow to include more code form GDS, any other useful HTML, and CSS snippets in the future.

## How to use
* [Install Emmet](https://emmet.io/) plugin to your code editor
* Install the JSON file in this repo to your Emmet folder, see [Emmet's documentation](https://docs.emmet.io/customization/snippets/#snippetsjson) for more details
* Type the snippet and hit `tab` or `ctrl + e`, many of the snippets then let you tab between placeholder areas, for example a radios id, name and value.

## What's included

### Layout
* `page`: Defaut page setup with a starter 3/4 column
* `grid`: Div with class of `.grid-row`.
* `colfull`: Div with class of `.column-full`.
* `colhalf`: Div with class of `.column-half`.
* `colthird` or `col1third`: Div with class of `.column-one-third`.
* `col2third` or `col2thirds`: Div with class of `.column-two-thirds`.
* `colquarter` or `col1quarter`: Div with class of `.column-one-quarter`.
* `col3quarter` or `col3quarters`: Div with class of `.column-three-quarters`.
* `aside`: Basic structure for adding complementary content, usually found on the right hand of the screen (on desktop layout).

### Forms
* `form`: Form tag with placeholder for action.
* `input`: Basic text input with placeholders for id, name, value.
* `inputdate`: Three inputs for day, month, year. Placeholders for legend (question), ids, names, values.
* `textarea`: Basic textarea, wrapped in `.form-group`. Placeholder for id, name, label.
* `radio`: Single radio with placeholders for id, name, value.
* `radioconditional`: Single radio with conditional content shown on select. Has placeholders for ids, names, values.
* `radioinline`: Two inline radios wrapped in `.form-group`.
* `radiostacked`: Three stacked radios wrapped in `.form-group`.
* `checkbox`: Single checkbox with placeholders for id, name, value.
* `checkboxconditional`: Single checkbox with conditional content shown on selcect. Has placeholders for ids, names, values.
* `checkboxinline`: Two inline checkboxes wrapped in `.form-group`.
* `checkboxstacked`: Three stacked checkboxes wrapped in `.form-group`.
* `button`: Anchor link with button class, placeholders for link and text.
* `start`: Anchor link with start button class, placeholders for link and text.
* `submit`: Input with type submit and button class, wrapped in `.form-group`. Placeholder for value.
* `select`: The dreaded dropdown, only use when necessary.


### Type
* `headingxl`: X-Large heading with placeholder for header tag, eg `H1`
* `headingl`: Large heading with placeholder for header tag, eg `H2`
* `headingm`: Medium heading with placeholder for header tag, eg `H3`
* `headings`: Small heading with placeholder for header tag, eg `H4`
* `bullets`: Unordered list with bullet list classes.
* `numbers`: Ordered list with number list classes.
* `legal`: Legal text markup with placeholder for message.
* `panel`: Left border to text with placeholder size of border and message.
* `progressive`: Expandable text with placeholder for link and message text.
* `data`: Data visualisation with placeholder for value and text.
