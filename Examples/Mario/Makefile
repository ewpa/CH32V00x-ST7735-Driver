all : flash

TARGET:=st7735_demo
TARGET_MCU?=CH32V003

ADDITIONAL_C_FILES+=st7735.c

include ./ch32fun/ch32fun.mk

flash : cv_flash
clean : cv_clean
