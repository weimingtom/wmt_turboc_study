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

## ctype.h
* int isalnum(int ch);
* int isalpha(int ch);
* int iscntrl(int ch);
* int isdigit(int ch);
* int isgraph(int ch);
* int islower(int ch);
* int isprint(int ch);
* int ispunct(int ch);
* int isspace(int ch);
* int isupper(int ch);
* int isxdigit(int ch);
* char *strcat(char *str1, char * str2);
* char *strchr(char *str, int ch);
* int strcmp(char *str1, char *str2);
* char *strcpy(char *str1, char *str2);
* unsigned int strlen(char *str);
* char *strstr(char *str1, char *str2);
* int tolower(int ch);
* int toupper(int ch);

## stdio.h
* void clearerr(FILE *fp);
* int close(int fp);
* int creat(char * filename, int mode);
* int eof(int fd);
* int fclose(FILE *fp);
* int feof(FILE *fp);
* int fgetc(FILE *fp);
* char *fgets(char *buf, int n, FILE *fp);
* FILE *fopen(char *filename, char *mode);
* int fpritnf(FILE *fp, char *format, args, ...);
* int fputc(char ch, FILE *fp);
* int fputs(char *str, FILE *fp);
* int fread(char *pt, unsigned size, unsigned n, FILE *fp);
* int fscanf(FILE *fp, char *format, args, ...);
* int fseek(FILE *fp, long offset, int base);
* long ftell(FILE *fp);
* int fwrite(char *ptr, unsigned size, unsigned n, FILE *fp);
* int getc(FILE *fp);
* int getchar(void);
* int getw(FILE *fp);
* int open(char *file_name, int mode);
* int printf(char *format, args, ...);
* int putc(int ch, FILE *fp);
* int putchar(char ch);
* int puts(char *str);
* int putw(int w, FILE *fp);
* int read(int fd, char *buf, unsigned count);
* int rename(char *oldname, char *newname);
* void rewind(FILE *fp);
* int scanf(char *format, args, ...);
* int write(int fd, char *buf, unsigned count);

## stdlib.h (or use malloc.h in the other compilers)
* void *calloc(unsigned n, unsigned size);
* void free(void *p);
* void *malloc(unsigned size);
* void *realloc(void *p, unsigned size);

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
