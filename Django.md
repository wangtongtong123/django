##Django
### from django.http omport HttpResponse
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
def hello(request):
    return HttpResponse("hello world")
    
    *django.http 模块导入（import）HttpsResponse类。*
    *hello是一个视图函数*
    *每个视图函数至少要有一个参数，通常叫做request.这是一个触发这个视图、包含当前web请求信息的对象，是类django。http.HttpRequest的一个实例。在这
个示例中*
    
  
