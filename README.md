# wmt_turboc_study
My Turbo C 2.0 / Turbo C++ 3.0 study

## Headers
* alloc.h, assert.h, bios.h, conio.h, ctype.h, dir.h, dos.h
* errno.h, fcntl.h, float.h, graphics.h, io.h, limits.h
* math.h, mem.h, process.h, setjmp.h, share.h, signal.h, stdarg.h
* stddef.h, stdio.h, stdlib.h, string.h, time.h, valufs.h

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
}
```
* char *asctime(struct tm *p);
* int clock_tclock();
* char *ctime(long *time);
* double difftime(time_t time2, time_t time1);
* struct tm *gmtime(time_t *time);
* time_t time(time_t time);
