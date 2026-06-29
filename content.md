To include a Mermaid diagram in an Atomic Learning `content.md` file, you should use standard Mermaid syntax within Markdown. For instance, the following code:

````markdown
```mermaid
graph TD
    accTitle: A Simple Mermaid Diagram
    accDescr {Contains two nodes: Node 1 and Node 2
        Node 1 is connected to Node 2 with a directed edge}
    A[Node 1] --> B[Node 2]
```
````

will render as 

```mermaid
graph TD
    accTitle: A Simple Mermaid Diagram
    accDescr {Contains two nodes: Node 1 and Node 2
        Node 1 is connected to Node 2 with a directed edge}
    A[Node 1] --> B[Node 2]
```

# Accessibility

You should specify the `accTitle` and `accDescr` values within the Mermaid diagram for accessibility. The description in `accDescr` will often describe the exact relationships in the diagram but, at least, it should convey the main purpose and important points of the diagram.
