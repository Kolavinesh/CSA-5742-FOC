echo "Enter a value: "
read a
echo "Enter a value: "
read b
echo "Enter a value: "
read c
d=$((b*b-4*a*c))
if [ $d -gt 0 ]
then
d=$(echo "$d" | awk '{print sqrt($1)}')
root1=$((-b+d/(2*a)))
root2=$((-b-d/(2*a)))
echo "root 1 is $root1"
echo "root 2 is $root2"
else
echo "there is no real roots"
fi
