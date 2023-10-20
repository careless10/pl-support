# Support Palestine

This is an repository that include code snippet for websites, that helps you create a "Support Palestine" Badge.

The link is dynamic and can be changed to any link you want, but the current link redirect to a donation page.

## Web

![Example image](web.png)
You can paste the following html code at the top of the `<body>` tag of your website to show the badge.

### Vanilla HTML

```html
<div
  style="
    padding: 16px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgb(38, 22, 22);
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 20px;
    box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.198);
    text-align: center;
  "
>
  <div
    style="
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    "
  >
    <p style="margin: 0; flex-grow: 2">
      🇵🇸 Stand with Palestine! Thousands of innocent people being murdered,
      <a
        style="color: rgb(183, 56, 56)"
        href="https://bit.ly/save-palestine-code"
      >
        Help Provide Humanitarian Aid to Palestine!.
      </a>
    </p>
  </div>
</div>

```

### React

```jsx
<div
  style={{
    padding: "16px",
    top: 0,
    left: 0,
    width: "100%",
    backgroundColor: "rgb(38, 22, 22)",
    color: "white",
    fontFamily: "Arial, Helvetica, sans-serif",
    fontWeight: "bold",
    fontSize: "20px",
    boxShadow: "2px 2px 2px rgba(0, 0, 0, 0.198)",
    textAlign: "center",
  }}
>
  <div
    style={{
      display: "flex",
      alignItems: "center",
      justifyContent: "space-between",
      flexWrap: "wrap",
    }}
  >
    <p style={{ margin: 0, flexGrow: 2 }}>
      🇵🇸 Stand with Palestine! Thousands of innocent people being murdered,
      <a
        style={{ color: "rgb(183, 56, 56)" }}
        href="https://bit.ly/save-palestine-code"
      >
        Help Provide Humanitarian Aid to Palestine!.
      </a>
    </p>
  </div>
</div>
```
