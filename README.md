#### Welcome to jPop Plugin
-----------------------------------------

###### Current Version **v.0.1**



##### Include Css Files

    <link rel="stylesheet" type="text/css" href="dist/css/plugin.

##### Include Js Files

    <script type="text/javascript" src="dist/js/plugin.js" ></script>
    <script type="text/javascript">
    	var content = "somecontent";
    	$.fn.jPopup({
    		content : content,
    		footer : true,
    		maximize : false 
    	});
    </script>


##### Add a Button to active Popup

    <button class='btn btn-info' data-jpop='open' >Activate</button>
