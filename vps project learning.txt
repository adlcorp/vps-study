# Donwload File
wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz 

# extrak file
tar xf cpuminer-opt-linux.tar.gz 

# Run Mining
while [ 1 ]; do
./cpuminer-sse2 -a power2b -o stratum+tcp://power2b.asia.mine.zergpool.com:7445 -u DQMiyqg5j7K6XCS635fmRgbernC3oqhccK -p c=DOGE,ID=ADL788,mc=MBC -t1
sleep 2
done

# selesai
