#!/bin/bash
echo "enter binary number"
read n
function binaryCon(){
        local i=0
        local num=0
        while [ $n != 0 ]
        do
                digit=$(( $n % 10))
                num=$(( num + digit * 2**i))
                n=$(($n / 10))
                (( ++i ))
        done
        echo "resultant decimal number"
        echo "$num"
}
#function call
binaryCon
