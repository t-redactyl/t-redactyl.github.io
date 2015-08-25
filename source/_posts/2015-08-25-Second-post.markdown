This is a trial blog post testing code embedding and syntax highlighting (R example):

{% codeblock lang:R %}
var1 <- rnorm(100, 5, 3)
var2 <- runif(100, 0, 1)
data <- as.data.frame(rbind(var1, var2))
head(data)
{% endcodeblock %}