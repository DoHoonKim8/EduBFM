# EduBfM Report

Name: DoHoonKim

Student id: 20170806

# Problem Analysis

Implement core APIs of buffer manager.

# Design For Problem Solving

## High Level

Buffer manager is the layer between main memory(RAM) and disk manager. Buffer manager's main functionality is to request a page to disk manager and retrieves the data and store it to buffer pool. The following are buffer manager's core APIs that can be called by the higher layer(main memory) or by the buffer manager itself:

- bfm_AllocTrain
- bfm_GetTrain
- bfm_ReadTrain
- bfm_FreeTrain
- bfm_FlushTrain
- bfm_FlushAll
- 

## Low Level

FILL WITH YOUR LOW LEVEL (CODE LEVEL) DESIGN

# Mapping Between Implementation And the Design

FILL WITH YOUR CODE IMPLEMENTATION DESCRIPTION
