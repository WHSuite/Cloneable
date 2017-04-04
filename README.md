Cloneable
=========

Javascript / jQuery cloneable items plugin

## Install (either:)

	yarn add jquery-cloneable
	npm install --save jquery-cloneable

## HTML

A simple example of a cloneable row would be:

	<div class="cloneable clone-container">
		<div class="clone-row">
			<label for="foo0">Employer's name</label>
			<input name="data[foo][0]" type="text" id="foo0">
			<a class="delete-item">Delete Item</a>
		</div>
		<a class="add-item">Add Item</a>
	</div>

## Init

After loading jQuery and this plugin, initialise cloneable with:

	$('.cloneable').cloneable();
