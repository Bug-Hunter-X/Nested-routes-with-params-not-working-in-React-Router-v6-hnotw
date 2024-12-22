# React Router v6 Nested Routes with Params Issue

This repository demonstrates a common issue encountered when using nested routes with parameters in React Router v6.  The problem arises when trying to access parameters from parent routes within child routes. The solution involves using the `useParams` hook correctly and understanding the route matching behavior.

## Problem

The original code attempts to access parameters from a parent route within a child route, but the child route receives undefined parameters.

## Solution

The solution involves using the `useParams` hook correctly within each component, ensuring that parameters are accessed from the correct route level. The updated code displays the parameters correctly.
