You can use  include statement in header file although most people doesnt't
follow this method.

Precautions for including include statement in header file:
1 . Only #include things you need to include
2 . Guard againts incidental multiple includes with include guards

Always guard your headers. Always always always.

Example:

#ifndef __MYCLASS_H_INCLUDED__
#define __MYCLASS_H_INCLUDED__


