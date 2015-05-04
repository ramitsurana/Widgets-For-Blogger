Steps to Add floating share buttons to blogger

Step 1: Open your blogger dashboard.

Step 2: Select your blog.

Step 3: Open Template option.

Step 4: Click Edit HTML. 

Step 5: In template code, search for <b:includable id=’post’ var=’post’>

Step 6: Just below it paste following code and save the template.

<!--floating share-->
<b:if cond='data:blog.pageType == "item"'>
<b:if cond='data:blog.pageType != "static_page"'>
<script src='http://s7.addthis.com/js/300/addthis_widget.js' type='text/javascript'></script>    
<div class='addthis_toolbox addthis_floating_style addthis_counter_style' style='position:fixed;  margin-left:-79px; float:left; top: 101px; background:#fff; border:3px solid #eeeeee;'>
<a class='addthis_button_facebook_like' fb:like:layout='box_count'/>
<a class='addthis_button_tweet' tw:count='vertical'/>
<a class='addthis_button_google_plusone' g:plusone:size='tall'/>
<br/>
<a class='addthis_counter'/>
 </div></b:if></b:if>
<!--floating share-->
