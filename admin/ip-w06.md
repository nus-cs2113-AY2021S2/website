{% macro show_main_text() %}
<div id="main">

<div id="title">

</div>
<div id="body">

<include src="dukeFragment.md" boilerplate var-header="**Duke - Ext: A-UserGuide**" var-fragment="extensions.mbdf#A-UserGuide" />
<include src="dukeFragment.md" boilerplate var-header="**Duke - Ext: A-Release**" var-fragment="extensions.mbdf#A-Release" />

</div>
</div>
{% endmacro %}

{% from "common/admin.njk" import show_admin_page with context %}
{{ show_admin_page("ip-w06", show_main_text) }}