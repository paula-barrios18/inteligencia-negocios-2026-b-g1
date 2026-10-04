## ETL steps & measures

The data types of the columns were checked to make sure that the data was correctly recognized in Power Query.
The Transaction ID column was checked for duplicate records, and no duplicates were found.
The Category and Item columns were cleaned using the Trim transformation to remove unnecessary spaces.
A conditional column called Rango de venta was created using the Total Spent column.
The conditional column classifies the records as Venta alta, Venta baja, or Sin dato.
Three DAX measures were created: Total Ventas using SUM, Promedio Venta using AVERAGE, and Gasto Promedio por Cantidad using DIVIDE.
The Total Ventas measure was also tested with a Location filter to observe the change in the filter context.