{\rtf1\ansi\ansicpg1252\cocoartf1561
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red27\green31\blue34;\red10\green77\blue204;}
{\*\expandedcolortbl;;\cssrgb\c14118\c16078\c18039;\cssrgb\c1176\c40000\c83922;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl600\sa320\partightenfactor0

\f0\b\fs48 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 CS7NS1 Individual Project - Distributed File System, Student ID:17303731 Name:Xiyu Yang\cf3 \strokec3 \
\cf2 \strokec2 List of Developed Modules\
\pard\pardeftab720\sl300\partightenfactor0

\fs30 \cf3 \strokec3 \
\pard\pardeftab720\sl360\sa320\partightenfactor0
\cf2 \strokec2 1.Distributed Transparent File Access\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\b0\fs32 \cf2 This is the core of any distributed file system and will consist of a server which provides access to files on the machine on which it is executed and a client side file service proxy that provides a language specific interface to the file system.\
\pard\pardeftab720\sl300\partightenfactor0

\b\fs30 \cf3 \strokec3 \
\pard\pardeftab720\sl360\sa320\partightenfactor0
\cf2 \strokec2 2.Caching\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\b0\fs32 \cf2 Caching is a vital element of any file system design that is required to give good performance and scale.\
\pard\pardeftab720\sl300\partightenfactor0

\b\fs30 \cf3 \strokec3 \
\pard\pardeftab720\sl360\sa320\partightenfactor0
\cf2 \strokec2 3.Directory Service\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\b0\fs32 \cf2 The directory service is responsible for mapping human readable, global file names into file identifiers used by the file system itself. A user request to open a particular file X should be passed by the client proxy to the directory server for resolution.\
\pard\pardeftab720\sl300\partightenfactor0

\b\fs30 \cf3 \strokec3 \
\pard\pardeftab720\sl360\sa320\partightenfactor0
\cf2 \strokec2 4.Lock Service\
\pard\pardeftab720\sl360\partightenfactor0

\b0\fs32 \cf2 This server simply holds a semaphore for each file it is told about. Any client wishing to access a file could simply ask for access from the lock server. Providing all other clients do the same, it can be sure that ot has exclusive access when access is granted.\
}