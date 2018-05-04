Javascript


Variable passing through the pages with LocalStorages



Suppose we have two web pages that pass variable content from on page to another page .


Page1.html 

<html>


		<body>

				<script type="text/javascript">


				window.onload = function() {
   							var getInput = prompt("Hey type something here: ");


   							localStorage.setItem("storageName",getInput);
											}
			
				</script>



		</body>
    
    Page2.html 
    
    <html>


		<body>

				<script type="text/javascript">


				window.onload = alert(localStorage.getItem("storageName"));

			
				</script>



		</body>


    
    
    
   


