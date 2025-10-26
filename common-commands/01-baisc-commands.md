### printing the number 1 to 100 which divided by 2 & 3 but 15
#!/bin/bash
#Author: Mouneh
#Date: 23-10-2025
#This scripts do 1-30 numbers here, only 2,3
set -x;
qii
for i in {1..30};
do
        if['expr $a %2==0']|| ['expr $a %3==0'];
        then
        echo 'the Numbers are' $a
       fi;
ne


#!/bin/bash
#Author: Mounesh
#Date: 23-10-2025
#This script prints numbers from 1–30, which are multiples of 2 or 3 but not 15.

set -x  # enable debug mode

for i in {1..30}
do
    if { [ $(expr $i % 2) == 0 ] || [ $(expr $i % 3) == 0 ]; } && [ $(expr $i % 15) != 0 ]; then
        echo "$i"
    fi
done
