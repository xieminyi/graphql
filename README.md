# README

## Methods
	
	query{
		getProduct (id){
			id
			name
			price
			description
			imageUrl
		} 
	}

	mutation{
		createProduct(input{
				name
				price
				description
				imageUrl
			})
		updateProduct(id,input{
				name
				price
				description
				imageUrl
			})
		deleteProduct(id)
	}

## Testing steps

  a) Update config.js for local mysql database

  b) Run server by "node server.js"

  c) Access server by http://localhost:5000, and graphql query by http://localhost:5000/graphql

