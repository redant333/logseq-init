icon:: 🍀

- ## background-color:: yellow
  background-color:: yellow
  #+BEGIN_QUERY
  {
  :title [:h3 "DOING"]
  :query (task "DOING")
  :group-by-page? false
  }
  #+END_QUERY
-
- #+BEGIN_QUERY
  {
  :title [:h3 "HIGH PRIORITY"]
  :query (and (task "TODO") [[highprio]])
  :group-by-page? false
  }
  #+END_QUERY
- query-table:: false
  #+BEGIN_QUERY
  {
  :title [:h3 "SHORT TERM"]
  :query (and (task "TODO") [[shortterm]] )
  :group-by-page? false
  }
  #+END_QUERY
- #+BEGIN_QUERY
  {
  :title [:h3 "LONG TERM"]
  :query (and (task "TODO") [[longterm]])
  :group-by-page? false
  }
  #+END_QUERY