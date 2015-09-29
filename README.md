# handlers_pending

An example of code block:

```
function test() {
  console.log("notice the blank line before this function?");
}
```

An example of code block with ruby highlight:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("This highlight for ruby code")
puts markdown.to_html
```
What the highlight code looks like if the readme is opened in a texteditor.
```
```ruby
require 'redcarpet'
markdown = Redcarpet.new("This highlight for ruby code")
puts markdown.to_html
```

An example of a table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
What the table looks like if the readme is opened in a text editor. 

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

An example of a table:

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
What this table looks like if the readme is opended in a text editor (notice that the pipes are not lined up).

```
| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
```
