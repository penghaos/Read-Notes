fs=10000;

N=5000;

n=0:N-1;

t=n/fs;

f=n*fs/N;

yy=fft(y,N);

mag=abs(yy)*2/N;

plot(f(6:46),mag(6:46))

title('彭浩——ts14060138')