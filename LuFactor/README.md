# luFactor
## Inputs
The input for the luFactor function in any square matrix A.
## Outputs
The outputs for the luFactor are three matrices L, U, and P.  L is a lower triangle matrix, when multiplied with U gives [P][A].  P is the pivot matrix, and U is an upper triangle matrix.
## Uses
This function is used to calculate the [L][U] factors of a matrix [A].
## How it works
My luFactor function first tests too see if the matrix is a square matrix, if it is not it will spit out an error.  If it is, it will go through the matrix A making sure to pivot when needed then it will use Gauss elimination to calculate the L and U matrices.  
