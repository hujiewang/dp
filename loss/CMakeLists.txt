FILE(GLOB luasrc *.lua)
ADD_TORCH_PACKAGE(dp/loss "${src}" "${luasrc}")
