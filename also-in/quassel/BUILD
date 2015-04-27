OPTS="$OPTS -DLINGUAS=\"$QUAS_LING\"" &&
#message o=$OPTS &&
if is_depends_enabled $SPELL kde-runtime;then
  default_build
else
  qt4_cmake_build
fi
