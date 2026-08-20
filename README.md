# wmt_turboc_study
My Turbo C 2.0 / Turbo C++ 3.0 study

## Documents
* https://www.freepascal.org/docs-html/rtl/graph/index-5.html
* https://home.cs.colorado.edu/~main/bgi/doc/index.html
* https://home.cs.colorado.edu/~main/bgi/doc/bgi.html
* https://code-reference.com/c/graphics.h
* https://github.com/actionanand/cppGraphicsExamples
* https://github.com/sagargoswami2001/Setup-Graphics.h-for-Visual-Studio-Code/blob/main/README.md
* https://github.com/ullaskunder3/Solution-to-graphics.h

## Download TC and TCC, based on DOSBox or DOSBox-X  
* dos.rar  
(dead) http://code.google.com/p/yangw80/   
https://code.google.com/archive/p/yangw80/downloads  
* (only asm) ASM_to_C_root.rar  
* Borland Turbo C 2.01  
https://archive.org/details/msdos_borland_turbo_c_2.01  
https://archive.org/download/msdos_borland_turbo_c_2.01/BorlandTurboC201-megapack.zip  
* Borland Turbo C++ 3.0  
https://archive.org/details/tcc_20210425  
https://archive.org/download/tcc_20210425/TCC.zip  
* Turbo C 32/64bit launcher  
https://sourceforge.net/projects/tc64bitlauncher/  
* Turbo C++  
https://sourceforge.net/projects/turbocpp.mirror/      
* DOSBox  
https://sourceforge.net/projects/dosbox/  
* DOSBox-X  
https://dosbox-x.com   

## Turbo C graphics.h, BGI, DOS    
* https://github.com/weimingtom/old_books_code  
* https://github.com/weimingtom/TurboCGraphics  
* https://github.com/search?p=1&q=Turbo+C+graphic&type=Repositories  
* OpenBGI  
https://sourceforge.net/projects/openbgi/  
* WinBGIm  
http://winbgim.codecutter.org  
* easyx  
http://www.easyx.cn  
* EGE  
https://github.com/misakamm/xege  
* search baidupan, [整理]project.rar  
* FreeDOS, search baidupan, dos.rar  
* https://github.com/yet-another-graphics-engine/YaGE  

## Other software for DOS
* DJGPP, DJGPP.rar (include djdev204_alpha.zip)  
https://www.delorie.com/djgpp/   
https://www.delorie.com/djgpp/dl/ofc/dlfiles.cgi/current/v2/  
* https://github.com/weimingtom/wmt_asm_study
* emu8086, emu8086v408r.exe, work_asm_tinybasic  
https://github.com/weimingtom/emu8086_playground  
https://github.com/AhmadNaserTurnkeySolutions/emu8086  
* dos.rar (27.73 MB)
```
C语言课程设计案例精编.7z
dosbox
BORLANDC, BC.EXE, BCC.EXE
disassem.exe
Fasm2
IDEasm
linux, LOADLIN.EXE
MASM
QB45
simc2000
TASM
TC20
TC30
tool: exe2bin.exe, EXE2COM.COM, notepad2.exe
VASM
vasmb
```
* ASM_to_C_root.rar
```
C32Asm
disassem.exe
Fasm
Fasm2
FASMW
IDEasm
MASM
masm32
masm32_8_2
MasmEdit
nasm
RadASM
TASM
tool: exe2bin.exe, EXE2COM.COM, notepad2.exe  
VASM
vasmb
W32asm
W32Dasm  V8
```
* 微机原理, weibo record
```
读大学时可能用过的微机原理软件：
（1）未来汇编（fasm）
（2）IDEasm，16位汇编集成环境
（3）Visual Assembly
（4）Visual ASM。
不是有人吐槽说学smalltalk没资料么，
我觉得汇编语言的资料也很少，
现在看来也非常难（当然一般用别的工具开发） ​​​

在旧硬盘找到一些proteus的资料（我当时有多喜欢51单片机），
感觉不看就很浪费。其实在大学里面51单片机是一个很模糊的课题，
它既可以归类到微机原理和x86汇编放在一起，也可以归类到数字电路，
和那些什么与非门和FPGA/CPLD放在一起。可惜电子界很多东西都是闭源的，
而那些开源的部分通常大学是不会讨论的（或者我读大学时
还没有这些开源的电子DIY课题），你现在看51单片机很多东西都
没有在开源中普及使用，都是什么Arduino、AVR之类

表面上是操作系统，其实是微机原理
表面上是微机原理，其实是intel汇编
表面上是数据结构，其实是编译原理

找了一堆电子版的操作系统书，不过我目前的程度还是看不懂。
我打算有时间买本intel汇编的书补一下，目前只是在做死记硬背
——套用某个老师的说法，把操作系统学成文科课——表现上它是操作系统，
其实是微机原理，或者是intel/atandt汇编；最好的单片机是PC 

仔细想想，汇编语言（微机原理）不就是操作系统的退化形态和子集？
我觉得我应该先把汇编弄懂 ​​​
```

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
* void far detectgraph(int far *graphdriver, int far *graphmode);
* void far drawpoly(int numpoints, int far *polypoints);
* void far ellipse(int x, int y, int stangle, int endangle, int xrandius, int yrandius);
* void far fillpoly(int numpoints, int far *polypoints);
* void far bloodfill(int x, int y, int border);
* void far getarccords(struct arccoordstype far *arccords);
* void far getaspectratio(int far *xasp, int far *yasp);
* int far getbkcolor(void);
* int far getcolor(void);
* void far getfillpattern(char far *upattern);
* void far getfillsetting(struct fillsettingstype far *fillinfo);
* int far getgraphmode(void)
* void far getimage(int left, int top, int right, int bottom, void far *bitmap);
* void far getlinesettings(struct linesettingstype far *lineinfo);
* int far getmaxcolor(void);
* int far getmaxx(void);
* int far getmaxy(void);
* void far getmoderange(int graphdriver, int far *lomode, int far *himode);
* void far gettextsettings(struct textsettingstype far *textinfo);
* void far getpalette(struct palettetype far *palette);
* int far getpixel(int x, int y);
* int far graphresult(void);
* unsigned far imagesize(int left, int top, int right, int bottom);
* void far initgraph(int far *graphdriver, int far *graphmode);
* void far line(int x0, int y0, int x1, int y1);
* void far linerel(int dx, int dy);
* void far lineto(int x, int y);
* void far moverel(int dx, int dy);
* void far moveto(int x, int y);
* void far outtext(char far *textstring);
* void far outtextxy(int x, int y, char far *textstring);
* void far pieslice (int x, int y, int stangle, int endangle, int radius);
* void far putimage(int x, int y, void far *bitmap, int op);
* void far putpixel(int x, int y, int pixelcolor);
* void far rectangle(int left, int top, int right, int bottom);
* int registerbgidriver(void (*driver)(void));
* int registerbgifount(void (*driver)(void));
* void far restorecrtmode(void);
* void far setactivepage(int pagenum);
* void far setallpalette(struct palettetype far *palette);
* void far setbkcolor(int color);
* void far setfillpattern(char far *pattern, int color);
* void far setcolor(int color);
* void far setfillstyle(int pattern, int color);
* unsigned far setgraphbufsize(unsigned bufsize);
* void far setgraphmode(int mode);
* void far setlinestyle(int linestyle, unsigned upattern, int thickness);
* void far setpalette(int index, int actual_color);

## C语言的图形函数

### 图形模式控制函数:
* initgraph
* closegraph, restorecrtmode
* setcolor, setbkcolor
* cleardevice

### 基本图形函数:
* putpixel
* line, lineto, linerel
* moveto, moverel
* circle, arc, ellipse
* rectangle
* drawpoly
* getmaxx, getmaxy
* getx, gety
* getpixel
* setlinestyle
* getlinesettings
* bar
* setfillstyle
* getfillsettings
* floodfill

### 图形屏幕操作函数:
* setviewport
* clearviewport
* setactivepage
* setvisualpage
* imagesize
* getimage
* putimage

### 图形模式下文本的输出:
* outtext, outtextxy
* settextstyle

