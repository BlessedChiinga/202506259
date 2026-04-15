# 202506259
FIBONACCI

#WORKFLOW

Start

Input a number n

Check if n = 0:

 If Yes, return 0 and end
 
 If No, go to next step

Check if n = 1:

 If Yes, return 1 and end

 If No, go to next step

Calculate Fibonacci:
return fib(n-1) + fib(n-2)

Return the result

End





#PSUEDOCODE

BEGIN

FUNCTION fib(n)

    IF n = 0 THEN
        RETURN 0

    ELSE IF n = 1 THEN
        RETURN 1

    ELSE
        RETURN fib(n - 1) + fib(n - 2)

    ENDIF

END FUNCTION

END





#PYTHON CODE

def fib(n):

    if n == 0:

        return 0

    elif n == 1:

        return 1

    else:

        return fib(n-1) + fib(n-2)