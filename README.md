# e-learn
A learning platform to all beginner.

#Work Flow
1.It has Video lecture 
2.It has lecture Note + Assignment Problem

#creating virtual env
-> virtualenv myenv
->source ./myenv/Scripts/activate

#creation of templates folder:-
app_name/templates/app_name/html_file.html

URL PATTERN SAMPLE:-
    path('admin/', admin.site.urls),
    path('',include('homeapp.urls')),
    path('blog/',include('blog.urls')),
    path('contact/',include('contact.urls'))

