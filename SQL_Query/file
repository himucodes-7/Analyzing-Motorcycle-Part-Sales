-- Start coding here
SELECT
	product_line,
	TO_CHAR(date,'Month') as month,
	warehouse,
from public.sales  -- please ensure that file location is correct  
where client_type = 'Wholesale'
group by product_line,
	TO_CHAR(date,'Month'),
	warehouse
order by product_line,TO_CHAR(date,'Month'),net_revenue DESC ;


