Este patch corrige o erro de linkagem da libart no host linux_x86_64, substituindo entrypoints de assembly por stubs em C++.

Instruções de Instalação:

Copiar stubs_host.cc para art/runtime/arch/x86_64/

Substituir o art/runtime/Android.bp pelo arquivo deste repositório.
