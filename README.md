Contains a Matrix class that takes ( rows , colomns , data = [] ) as input. 
Written in JS since JS doesn't has matrix funtionals.

m1 = new Matrix(2, 2, [ [1,2] , 
                        [1,2] ] );
												
m2 = new Matrix(2, 2, [ [2,2] ,
                        [2,2] ] );
 
 
Matrix class dontains functions like -> 
- addition            -> Matrix.add( m1, m2 ) 
- subtraction         -> Matrix.sub( m1, m2 )
- multiplication      -> Matrix.mul( m1, m2 ) 
- dot product         -> Matrix.dotProduct( m1, m2 )
- transpose           -> Matrix.trans( m1 )
- mapping a function  -> Matrix.map( m1 , function_to_map )  
                                        to each value 
                                       
                                        
