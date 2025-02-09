# React Router Catch-All Route Placement Bug

This repository demonstrates a common error in React Router v6, where the catch-all route (`*`) is placed incorrectly, preventing other routes from working correctly. 

The bug is caused by the catch-all route being placed before other more specific routes.  This means the catch-all route will always match, regardless of the URL.

The solution shows how to correctly place the catch-all route at the end of the `Routes` component to allow more specific routes to be matched first.