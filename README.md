# c-programmmain( )
 {
 int radius ;
 float area, perimeter ;
 printf ( "\nEnter radius of a circle " ) ;
 scanf ( "%d", &radius ) ;
 areaperi ( radius, &area, &perimeter ) ;
 printf ( "Area = %f", area ) ;
 printf ( "\nPerimeter = %f", perimeter ) ;
 }
 areaperi ( int r, float *a, float *p )
 {
22226
 2
 *a = 3.14 * r * r ;
 *p = 2 * 3.14 * r ;
 }
