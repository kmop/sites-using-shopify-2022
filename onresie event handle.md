#### Settings

```javascript
{
    onresize : function() {
        // console.log("onresize =>", this, this.id, this.settings);
    }
}
```

    state.loaded
           > bind onresize event
               > window.onresize, editormd watch/unwatch/fullscreen/fullscreenExit/toolbar show|hide
                   > trigger onresize event handle