IOP_BIN = AllowDVDV.irx
IOP_OBJS = AllowDVDV.o imports.o

IOP_CFLAGS += -Wall -fno-builtin -D_IOP
IOP_LDFLAGS += -s
IOP_INCS += -I$(PS2SDKUJ)/iop/include -I$(PS2SDKUJ)/common/include

all: $(IOP_BIN)

clean:
	rm -f $(IOP_BIN) $(IOP_OBJS)

include $(PS2SDKUJ)/Defs.make
include ../Rules.make
