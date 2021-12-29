


KogWheel Feature 1
```
#!/usr/bin/env bash

## References
# https://stackoverflow.com/a/10383546/14346786
# https://security.web.cern.ch/advisories/spectre-meltdown/spectre-meltdown.shtml
# https://security.web.cern.ch/advisories/spectre-meltdown/spectre-meltdown-checker.sh
# https://security.web.cern.ch/advisories/spectre-meltdown/spectre-cpu-microcode-checker.sh


# XXX # Original pstatus
# print status function
# pstatus() {
# 	  case "$1" in
# 			  red)    col="\033[101m\033[30m";;
# 			  green)  col="\033[102m\033[30m";;
# 			  yellow) col="\033[103m\033[30m";;
# 			  blue)   col="\033[104m\033[30m";;
# 			  *)      col="";;
# 	  esac
# 	  /bin/echo -ne "$col $2 \033[0m"
# 	  [ -n "$3" ] && /bin/echo -n " ($3)"
# 	  /bin/echo
# }


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
