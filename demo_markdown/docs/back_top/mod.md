# Back Top

BackTop will find its first scrollable ascendant element and listen scroll event on it.

```rust demo
view! {
    <BackTop />
}
```

### Visibility height

```rust demo
view! {
    <BackTop bottom=100 visibility_height=280>
        <div style="width: 200px; text-align: center;">
            "Visibility Height: 280px"
        </div>
    </BackTop>
}
```

### Change position

```rust demo
view! {
    <BackTop right=40 bottom=160>
        <div style="width: 200px; text-align: center;">
            "Change Position"
        </div>
    </BackTop>
}
```

### BackTop Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| class | `OptionalProp<MaybeSignal<String>>` | `Default::default()` | Addtional classes for the back top element. |
| right | `MaybeSignal<i32>` | `40` | The width of BackTop from the right side of the page. |
| bottom | `MaybeSignal<i32>` | `40` | The height of BackTop from the bottom of the page. |
| bottom | `MaybeSignal<i32>` | `180` | BackTop's trigger scroll top. |
| children | `Option<Children>` | `None` | BackTop's content. |

<div style="height: 600px">
</div>
