### div 안에 한 번에 넣어서 랜더링이 가능하다.

```
const container = React.createElement(
    "div",
    null,
    [span, btn]
);

ReactDOM.render(container, root);

```

