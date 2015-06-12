[{
	"$project" : { "Type" : "Local Project",
					"Name" : "Aquarius",
					"Description" : "TSistema de ventas para farmacias, con carritos de compras, web services, factura de la compra",
					"From" : { "$django" : { "Version" : "1.5.1"},},
					"Group" : { "G" : "Public", "B" : "Private", "H" : "Deploy"},
					"_id" : 1
				 },
}]