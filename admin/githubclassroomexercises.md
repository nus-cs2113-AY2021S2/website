{% from "common/admin.njk" import show_admin_page with context %}

{% call show_admin_page("githubclassroomexercises") %}
<div id="main">

<iframe src="{{ url_ghclassroom_ex }}" width="800" height="1000" ></iframe>

<br>


</div>

{% endcall %}
