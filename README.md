## Repo for the Machine Learning in Science collquium webpage at the University of Glasgow

Notes:
	- get rid of table hovering color by commenting out ".rendered_html tbody tr:hover" in html file
	- show the contents of first cell and bring back "in[]/out[]" prompt margins by opening the .pynb 
	  file in VScode and looking for first cell contents: 
		"source": [
 		   "from IPython.core.display import display,HTML\n",
 		   "display(HTML('<style>div.prompt {display:none}</style>'))\n",
  		  "display(HTML('<style>div.input{display:none;}</style>'))"
 		  ]