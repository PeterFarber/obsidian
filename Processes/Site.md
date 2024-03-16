<main>
	<div class="bar red"></div>
	
	<div class="box var">
		<label>DataStores:</label>
		<span class="array"><b>DataStore</b></span>
	</div>
	
	<div class="box func">
		<label>AddEntry</label>
	</div>
	<div class="box func">
		<label>GetDataStores</label>
	</div>

The <a data-href="Site" href="Site" class="internal-link red" target="_blank" rel="noopener">Site</a> contains the core functionality of storing analytics. 

When a request is made to add an **Entry**, the <a data-href="Site" href="Site" class="internal-link red" target="_blank" rel="noopener">Site</a> will propagate the data down to the latest <a data-href="DataStore" href="DataStore" class="internal-link orange" target="_blank" rel="noopener">DataStore</a> to be stored for later retrieval.

When a request is made to retrieve the data we just send back a list of all of the <a data-href="DataStore" href="DataStore" class="internal-link orange" target="_blank" rel="noopener">DataStores</a> which can then be used to pull the required data.

</main>
