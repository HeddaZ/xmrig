Microsoft Visual Studio 2019
----------------------------
Download and install Visual Studio Community 2019 , during install choose following components: Desktop development with C++ (left side) and C++/CLI support for v142 build tools (right side).  
Download and install git , default setup parameters are fine.  

1. git clone https://github.com/xmrig/xmrig.git
2. mkdir xmrig\build && cd xmrig\build
3. cmake .. -G "Visual Studio 16 2019" -A x64 -DXMRIG_DEPS=D:\Workspace\xmrig\libs\msvc2019\x64
4. cmake --build . --config Release