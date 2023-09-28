# Logseq to Hugo Action
Github action to publish logseq graph as a hugo static site.
Using the awesome [logseq-to-markdown](https://github.com/dom8509/logseq-to-markdown) project.

# logseq-hugo-action
Github action to publish logseq graph as a hugo static site

## Inputs

### `graph-name`

**Required** The name of the logseq graph to export. Default is current path folder name: `$(basename "$PWD")`.

### `options`

Additional params for logseq-to-markdown execution:


## Example usage

```yaml
uses: atfornes/logseq-hugo-action
with:
  graph-name: 'MyJournal'
  options: "-o content"
```
