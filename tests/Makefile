SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/xor_gate.v
xor:

$(MAKE) sim MODULE=xor_test TOPLEVEL=xor_gate

include $(shell cocotb-config --makefiles)/Makefile.sim
