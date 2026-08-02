# wmt_turboc_study
My Turbo C 2.0 / Turbo C++ 3.0 study

## Headers
* alloc.h, assert.h, bios.h, conio.h, ctype.h, dir.h, dos.h
* errno.h, fcntl.h, float.h, graphics.h, io.h, limits.h
* math.h, mem.h, process.h, setjmp.h, share.h, signal.h, stdarg.h
* stddef.h, stdio.h, stdlib.h, string.h, time.h, valufs.h

## math.h
* int abs(int x);
* double acos(double x);
* double asin(double x);
* double atan(double x);
* double atan2(double x, double y);
* double cos(double x);
* double cosh(double x);
* double exp(dobule x);
* double fabs(double x);
* double floor(double x);
* double fmod(double x, double y);
* double frexp(double val, int *eptr);
* double log(double x);
* double log10(double x);
* dobule modf(double val, double iptr);
* double pow(doble x, double y);
* int rand(void);
* double sin(double x);
* dobule sinh(double x);
* dobule sqrt(doiuble x);
* double tan(double x);
* double tanh(double x);

## time.h
* struct tm
```
struct tm {
int tm_sec;
int tm_min;
int tm_hour;
int tm_mday;
int tm_mon;
int tm_year;
int tm_wday;
int tm_yday;
int tm_isdst;
};
```
* char *asctime(struct tm *p);
* int clock_tclock();
* char *ctime(long *time);
* double difftime(time_t time2, time_t time1);
* struct tm *gmtime(time_t *time);
* time_t time(time_t time);
