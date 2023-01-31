# This is the header

## A slightly smaller hearer

### Even smaller

#### Way smaller

##### c'mon now...
  
        
###### ...the smallest.



![image of SF](https://images.pexels.com/photos/1141853/pexels-photo-1141853.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)
##### I added a picture, look! :grin:

That's a **nice** _bridge_. It has good vibes :star: :fire: :confetti_ball: :sunrise_over_mountains:  

&nbsp;  
### I can also make lists, check it out

 * here's
 * a
 * list
   * with indentations for sub points
 * that's
 * pretty
 * cool, eh?  
 &nbsp;  
1. I can also
2. Do numbered lists
3. If needed.  

&nbsp;  

Another cool thing that I can do is highlight code, like below:

`SELECT
  your mum
 FROM
  your butt
 WHERE
  your butt is big`. 
&nbsp;  
&nbsp;  
I can also create 'code blocks' to show longer sections of code:


```sql
SELECT 
  m.title, 
  COUNT(*),
  AVG(r.rating)
  
FROM
  renting AS r
  LEFT JOIN customers AS c
  ON c.customer_id = r.customer_id
    LEFT JOIN movies AS m
     ON m.movie_id = r.movie_id

WHERE
  c.date_of_birth BETWEEN '1970-01-01' AND '1979-12-31'

GROUP BY
  m.title
  
HAVING COUNT
  (*) > 1 -- Remove movies with only one rental
  
ORDER BY
  AVG(r.rating) DESC; -- Order with highest rating first
```


This is some code that I was practicing on in **_Datacamp_**
