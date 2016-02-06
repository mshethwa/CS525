Personnel information:
1. Qi Yang
2. Bo Peng
3. Mohammed Shethwala
4. Bilal Syed

File list:
1. storage_mgr.c
2. storage_mgr.h
3. dberror.c
4. dberror.h
5. test_helper.h
6. test_assign1_1.c
7. README.txt

Milestone:
1. Use of structure SM_FileHandle to store the open page file done.
2. Functions for manipulating page files done.
3. functions for reading blocks of file done.
4. functions for writing blocks to file done. 


Installation instruction:


Function descriptions: of all additional functions
1. joinString: This function is used to join two *char type variables together. This function is mainly used to join the paths of the file which is used in the program

2. find size: This function is used to calculate the size of the given file. It is used in multiple functions to get the size of the open file.

Additional error codes: of all additional error codes (leave if blank if there isn't any)
#define RC_READ_FAILED 5
#define RC_READ_NON_EXISTING_PAGE 6
#define RC_UNESPECTED_ERROR 7
#define RC_SET_POINTER_FAILED 100
#define RC_GET_NUMBER_OF_BYTES_FAILED 101
#define RC_UNPIN_ERROR 401
#define RC_NO_FREE_BUFFER_ERROR  402
#define RC_NO_SUCH_PAGE_IN_BUFF  403

Data structure: main data structure used (leave if blank if there isn't any)

Extra credit: of all extra credits (leave if blank if there isn't any)

Additional files: of all additional files

Test cases: of all additional test cases added (leave if blank if there isn't any)

Problems solved (leave if blank if there isn't any)

Problems to be solved (leave if blank if there isn't any):
1. Testing remaning

