X_ASFLAGS	:= -f elf -I xlibc/include
X_INCDIRS	:= xlibc/include

SRC			:= arch/x86/*.asm arch/wordsize-32/*.c 
SRC			+= ansi/*.c arpa/*.c charset/*.c crypto/*.c ctype/*.c
SRC			+= environ/*.c locale/*.c malloc/*.c math/*.c socket/*.c stdio/*.c
SRC			+= stdlib/*.c string/*.c syslib/*.c time/*.c unistd/*.c
SRC			+= syslib/syscall.asm
SRC			+= gcc/*.c fphook/*.c

TARGET_TYPE	:= static
NAME		:= xlibc-0.0.1
