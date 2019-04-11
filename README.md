echo "finding even numbers range in 1 to 10"
for n in $(seq 1 10)
do 
rem=$(( $n % 2 ))
if [ $rem -eq 0 ]
then 
echo "$n is even number"
fi
done
