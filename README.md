# Computer Network
Lab Instruction ของรายวิชา Computer Network และ Internet Technology 


```php
// traditional markdown and parse full text
$parser = new \cebe\markdown\Markdown();
echo $parser->parse($markdown);

// use github markdown
$parser = new \cebe\markdown\GithubMarkdown();
echo $parser->parse($markdown);

// use markdown extra
$parser = new \cebe\markdown\MarkdownExtra();
echo $parser->parse($markdown);

// parse only inline elements (useful for one-line descriptions)
$parser = new \cebe\markdown\GithubMarkdown();
echo $parser->parseParagraph($markdown);
```
