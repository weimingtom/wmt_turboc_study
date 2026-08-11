# wmt_turboc_study
My Turbo C 2.0 / Turbo C++ 3.0 study

## Standard Headers
* math.h
* ctype.h
* stdio.h
* stdlib.h
* time.h
* assert.h, errno.h, float.h, limits.h, setjmp.h, signal.h, stdarg.h, stddef.h, string.h  

## Non-standard headers
* dos.h
* graphics.h
* alloc.h, bios.h, conio.h, dir.h, fcntl.h, io.h, mem.h, process.h, share.h, valufs.h  

## Unsupported standard headers
* complex.h, fenv.h, inttypes.h, iso646.h, locale.h, stdbool.h, stdint.h, tgmath.h, wchar.h, wctype.h   

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

## stdlib.h
* div_t
```
struct div_t {
int quot;
int rem;
};
```
* ldiv_t
```
struct ldiv_t {
long int quot;
long int rem;
};
```
* void abort();
* int abs(int num);
* double atof(char *str);
* int atoi(char *str);
* long atol(char *str);
* void *bsearch(void key, void *base, unsigned int num, unsigned int size, int (*compare)());
* void exit(int status);
* div_t div(int num, int denom);
* char *itoa(int num, char *str, int radix);
* long labs(long num);
* ldiv_t ldiv(long int num, long int denom);
* char *ltoa(long num, char *str, int radix);
* void qsort(void *base, unsigned int num, unsigned int size, int (*comp)());
* int rand();
* double strtod(char *start, char **end);
* long int strtol(char *start, char **end, int radix);
* unsigned long int strtoul(char *start, char **end, int radix);
* int system(char *str);

## dos.h
* int bdos(int dosfun, unsigned dosdx, unsigned dosa1);
* void getdate(struct date *dateblk);
```
struct date {
int da_year;
int da_day;
int da_mon;
};
```
* void getfat(int drive; struct fatinfo *fatblkp);
```
struct fatinfo {
char fi_sclus;
char fi_fatid;
int fi_nclus;
int fi_bysec;
};
```
* int getftime(int handle, struct time *ftimep)
* int inport(int port);
* int inportb(int port);
* int int86(int intr_num, union REGS *inregs, union REGS *outregs);
* int intdos(union REGS inregs, union REGS outregs);
* void keep(int status, int size);
* void outp(int port, int value);
* void outport(int port, int word);
* void outportb(int port, char byte);
* int peek(int segment, unsigned offset);
* int peekb(int segment, unsigned offset);
* void poke(int segment, int offset, int value);
* void pokeb(int segment, int offset, char value);
* int randbrd(struct fcb *fcbptr, int reccnt);
* int randbwr(struct fcb *fcbptr, int reccnt);
* void seeread(struct SREGS *segtbl);
* void setdate(struct date *dateblk);
* void settime(struct time * timep);
```
struct time {
unsigned char ti_min;
unsigned char ti_hour;
unsigned char ti_hund;
unsigned char ti_sec;
};
```
* unsigned sleep(unsigned seconds);
* void sound(unsigned frequency);
* void clreol(void);
* void clrscr(void);
* void delline(void);
* void gettextinfo(struct text_info *inforec);
* int gettext(int left, int top, int right, int bottom, void *destinfo);
* void gotoxy(int x, int y);
* void highvideo(void);
* void insline(void);
* void lowvideo(void);
* int movetext(int left, int top, int right, int bottom, int newleft, int newtop):
* void normvideo(void);
* int puttext(int left, int top, int right, int bottom, void *source);
* void textattr(int attribute);
* void textbackground(int color);
* void textcolor(int color);
* void textmode(int mode);
* int wherex(void);
* int wherey(void);
* void window(int left, int top, int right, int bottom);

## graphics.h
* void far arc(int x, int y, int stangle, int endangle, int radius);
* void far bar(int left, int top, int right, int bottom);
* void far bar3d(int left, int top, int right, int bottom, int depth, int topflag);
* void far circle(int x, int y, int radius);
* void far cleardevice(void);
* void far clearviewport(void);
* void far closegraph(void);
* 
