################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL := cmd.exe
RM := rm -rf

USER_OBJS :=

LIBS := 
PROJ := 

O_SRCS := 
C_SRCS := 
S_SRCS := 
S_UPPER_SRCS := 
OBJ_SRCS := 
ASM_SRCS := 
PREPROCESSING_SRCS := 
OBJS := 
OBJS_AS_ARGS := 
C_DEPS := 
C_DEPS_AS_ARGS := 
EXECUTABLES := 
OUTPUT_FILE_PATH :=
OUTPUT_FILE_PATH_AS_ARGS :=
AVR_APP_PATH :=$$$AVR_APP_PATH$$$
QUOTE := "
ADDITIONAL_DEPENDENCIES:=
OUTPUT_FILE_DEP:=
LIB_DEP:=
LINKER_SCRIPT_DEP:=

# Every subdirectory with source files must be described here
SUBDIRS := 


# Add inputs and outputs from these tool invocations to the build variables 
C_SRCS +=  \
../blinkm.cpp \
../buzzer.cpp \
../cardreader.cpp \
../configuration_store.cpp \
../dac_mcp4728.cpp \
../digipot_mcp4451.cpp \
../M100_Free_Mem_Chk.cpp \
../MarlinSerial.cpp \
../Marlin_main.cpp \
../mesh_bed_leveling.cpp \
../planner.cpp \
../qr_solve.cpp \
../Sd2Card.cpp \
../SdBaseFile.cpp \
../SdFatUtil.cpp \
../SdFile.cpp \
../SdVolume.cpp \
../servo.cpp \
../stepper.cpp \
../stepper_dac.cpp \
../stepper_indirection.cpp \
../stopwatch.cpp \
../temperature.cpp \
../twibus.cpp \
../ultralcd.cpp \
../vector_3.cpp \
../watchdog.cpp


PREPROCESSING_SRCS += 


ASM_SRCS += 


OBJS +=  \
blinkm.o \
buzzer.o \
cardreader.o \
configuration_store.o \
dac_mcp4728.o \
digipot_mcp4451.o \
M100_Free_Mem_Chk.o \
MarlinSerial.o \
Marlin_main.o \
mesh_bed_leveling.o \
planner.o \
qr_solve.o \
Sd2Card.o \
SdBaseFile.o \
SdFatUtil.o \
SdFile.o \
SdVolume.o \
servo.o \
stepper.o \
stepper_dac.o \
stepper_indirection.o \
stopwatch.o \
temperature.o \
twibus.o \
ultralcd.o \
vector_3.o \
watchdog.o

OBJS_AS_ARGS +=  \
blinkm.o \
buzzer.o \
cardreader.o \
configuration_store.o \
dac_mcp4728.o \
digipot_mcp4451.o \
M100_Free_Mem_Chk.o \
MarlinSerial.o \
Marlin_main.o \
mesh_bed_leveling.o \
planner.o \
qr_solve.o \
Sd2Card.o \
SdBaseFile.o \
SdFatUtil.o \
SdFile.o \
SdVolume.o \
servo.o \
stepper.o \
stepper_dac.o \
stepper_indirection.o \
stopwatch.o \
temperature.o \
twibus.o \
ultralcd.o \
vector_3.o \
watchdog.o

C_DEPS +=  \
blinkm.d \
buzzer.d \
cardreader.d \
configuration_store.d \
dac_mcp4728.d \
digipot_mcp4451.d \
M100_Free_Mem_Chk.d \
MarlinSerial.d \
Marlin_main.d \
mesh_bed_leveling.d \
planner.d \
qr_solve.d \
Sd2Card.d \
SdBaseFile.d \
SdFatUtil.d \
SdFile.d \
SdVolume.d \
servo.d \
stepper.d \
stepper_dac.d \
stepper_indirection.d \
stopwatch.d \
temperature.d \
twibus.d \
ultralcd.d \
vector_3.d \
watchdog.d

C_DEPS_AS_ARGS +=  \
blinkm.d \
buzzer.d \
cardreader.d \
configuration_store.d \
dac_mcp4728.d \
digipot_mcp4451.d \
M100_Free_Mem_Chk.d \
MarlinSerial.d \
Marlin_main.d \
mesh_bed_leveling.d \
planner.d \
qr_solve.d \
Sd2Card.d \
SdBaseFile.d \
SdFatUtil.d \
SdFile.d \
SdVolume.d \
servo.d \
stepper.d \
stepper_dac.d \
stepper_indirection.d \
stopwatch.d \
temperature.d \
twibus.d \
ultralcd.d \
vector_3.d \
watchdog.d

OUTPUT_FILE_PATH +=Marlin.elf

OUTPUT_FILE_PATH_AS_ARGS +=Marlin.elf

ADDITIONAL_DEPENDENCIES:=

OUTPUT_FILE_DEP:= ./makedep.mk

LIB_DEP+= 

LINKER_SCRIPT_DEP+= 


# AVR32/GNU C Compiler























































./%.o: .././%.cpp
	@echo Building file: $<
	@echo Invoking: AVR8/GNU C Compiler : 4.9.2
	$(QUOTE)C:\Program Files (x86)\Atmel\Studio\7.0\toolchain\avr8\avr8-gnu-toolchain\bin\avr-g++.exe$(QUOTE) -funsigned-char -funsigned-bitfields -DDEBUG -DARDUINO=10600 -DF_CPU=16000000L  -I"C:\Program Files (x86)\Atmel\Studio\7.0\Packs\atmel\ATmega_DFP\1.0.106\include" -I"C:\Program Files (x86)\Arduino\hardware\arduino\avr\cores\arduino" -I"C:\Program Files (x86)\Arduino\hardware\arduino\avr\variants\mega" -I"C:\Program Files (x86)\Arduino\libraries\LiquidCrystal"  -O3 -fno-exceptions -ffunction-sections -fdata-sections -fpack-struct -fshort-enums -mrelax -g2 -Wall -mmcu=atmega2560 -B "C:\Program Files (x86)\Atmel\Studio\7.0\Packs\atmel\ATmega_DFP\1.0.106\gcc\dev\atmega2560" -c -MD -MP -MF "$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -MT"$(@:%.o=%.o)"   -o "$@" "$<" 
	@echo Finished building: $<
	



# AVR32/GNU Preprocessing Assembler



# AVR32/GNU Assembler




ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: $(OUTPUT_FILE_PATH) $(ADDITIONAL_DEPENDENCIES)

$(OUTPUT_FILE_PATH): $(OBJS) $(USER_OBJS) $(OUTPUT_FILE_DEP) $(LIB_DEP) $(LINKER_SCRIPT_DEP)
	@echo Building target: $@
	@echo Invoking: AVR8/GNU Linker : 4.9.2
	$(QUOTE)C:\Program Files (x86)\Atmel\Studio\7.0\toolchain\avr8\avr8-gnu-toolchain\bin\avr-g++.exe$(QUOTE) -o$(OUTPUT_FILE_PATH_AS_ARGS) $(OBJS_AS_ARGS) $(USER_OBJS) $(LIBS) -Wl,-Map="Marlin.map" -Wl,--start-group -Wl,-lm  -Wl,--end-group -Wl,--gc-sections -mrelax -mmcu=atmega2560 -B "C:\Program Files (x86)\Atmel\Studio\7.0\Packs\atmel\ATmega_DFP\1.0.106\gcc\dev\atmega2560"  
	@echo Finished building target: $@
	"C:\Program Files (x86)\Atmel\Studio\7.0\toolchain\avr8\avr8-gnu-toolchain\bin\avr-objcopy.exe" -O ihex -R .eeprom -R .fuse -R .lock -R .signature -R .user_signatures  "Marlin.elf" "Marlin.hex"
	"C:\Program Files (x86)\Atmel\Studio\7.0\toolchain\avr8\avr8-gnu-toolchain\bin\avr-size.exe" "Marlin.elf"
	
	





# Other Targets
clean:
	-$(RM) $(OBJS_AS_ARGS) $(EXECUTABLES)  
	-$(RM) $(C_DEPS_AS_ARGS)   
	rm -rf "Marlin.elf" "Marlin.a" "Marlin.hex" "Marlin.lss" "Marlin.eep" "Marlin.map" "Marlin.srec" "Marlin.usersignatures"
	