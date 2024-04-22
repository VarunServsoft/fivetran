with cte as (select * from (source('PC_FIVETRAN_DB','ORDERS'))
),FINAL as (select * from cte where SHIP_MODE = 'Second Class')
select * from FINAL