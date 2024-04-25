```ts
class Article {
  private _lists: any[] = []
  
  public get articles(): any[]{
    return this._list.map(article => {
      article.title = article.title.substr(0,2)
      return article
    })
  }
  
  public set articles(lists:any[]){
    this._lists = lists
  }
}
```

