# makingcryptogreat



<!DOCTYPE html>
<html lang="en">
<head>
		<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
	
	
	<nav class="navbar navbar-default">
		<div class="container-fluid">
			
			<!-- Logo -->
			<div class="navbar-header">
				<a href="#" class="navbar-brand">Sentence Sampler</a>
			</div>


			<!-- Menu Items -->
			
			<div>
				<ul class="nav navbar-nav">
					<li class="active">
						<a href="">Home</a>
					</li>

					<li >
						<a href="">About</a>
					</li>

					<li>
						<a href="">Others</a>
					</li>
				</ul>
			</div>


		</div>
	</nav>

	<div class="container-fluid">

		<div class="container">
			<h2>Article Sampler</h2>
			<button class="btn btn-default" style="margin-left:auto; margin-right:auto" onclick="launch()">Click to randomly sample 30 articles</button>

			<!-- The class=table is very important -->
			<!-- Can also add table-condensed and table-striped classes do alter appearance (they overide default) The class table should be kept-->
			<table class="table table-striped" id="dataTable">
				<thead>
					<tr>
						<th>New York Times</th>
						<th>The Guardian</th>
					</tr>
				</thead>

				<tbody>
				</tbody>
			</table>
		</div>
		
		<div class="container"><div id="status" class="alert alert-success">This will take about 30 to 60 seconds...</div></div>

		<div class="container">
			<h2>Sentence Sampler</h2>
			<p></p>

			<p>HTML goes here:</p>
			<p></p>
			<textarea name="htmlTextBox" cols="120" rows="20" id="textBox"></textarea>
			<p></p>
			<button class="btn btn-default" onclick="parseHTML()">Submit</button>
		</div>
		
	</div>



	<script src="SentenceLengthSampler.js" type="text/javascript"></script>

</body>
</html>



