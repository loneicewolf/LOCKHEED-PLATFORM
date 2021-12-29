


KogWheel Feature 1
```
ABC() {
  for i in {"abc","def","","jkl"}; do
    case "$i" in 
      abc)      echo "kogwheel 1 $i";;
      def)      echo "kogwheel 2 $i";;
      ghi)      echo "kogwheel 3 $i";; # -----x
      jkl)      echo "kogwheel 4 $i";; #      |
                                       #      v
      *)      echo "wildstar";; # if e.g    "ghi" wasn't found
                                # we print "wildstar"
    
    esac
      /bin/echo -ne "$col $2 \033[0m"
      [ -n "$3" ] && /bin/echo -n " ($3)"
      /bin/echo
  done

# END of Function #
# Export func. ABC as a function (-f)
}; export -f ABC
```
