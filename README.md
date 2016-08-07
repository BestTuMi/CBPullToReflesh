#CBPullToReflesh

<center>![](https://d13yacurqjgara.cloudfront.net/users/141880/screenshots/2542648/dailyui-094.gif "Demo GIF Animation")</center>

**Dribbble**网址：[Daily-UI-094-News](https://dribbble.com/shots/2542648-Daily-UI-094-News)

## Usage

### Wrap your scrollView

``` 
let tableViewWrapper = PullToRefleshView(scrollView: yourTableView)
bodyView.addSubview(tableViewWrapper)
```
The color of the wrapper will be same as your scrollView's background color.


### Handler

``` 
tableViewWrapper.didPullToRefresh = {
   //you can do anythings you want after beginning to reflesh
}
```
You can end the reflesh simplily 

```
 tableViewWrapper.endReflesh()
```


