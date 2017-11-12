在Controller中使用this.HttpContent只能取得HttpContextBase类型，要想取得HttpContext，必須使用

**this.HttpContext.ApplicationInstance.Context**

