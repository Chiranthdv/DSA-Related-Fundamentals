# DSA-Related-Fundamentals

# 1) Array:
    -> int[] b = Arrays.copyOf(arr, n);
    -> int[] c = Arrays.copyOfRange(arr, 2, 5);
    -> Arrays.toString(arr);
    -> Arrays.equals(arr1, arr2);

# 2) ArrayList:
     -> list.add(value); list.add(index, value);
     -> list.get(index);
     -> list.set(index, value);
     -> list.remove(index);    // by index   list.remove(Object o); // by value
     -> list.size();
     -> list.contains(value);
     -> list.clear();
     -> list.isEmpty();
     -> list.indexOf(value);   list.lastIndexOf(value);
     -> Collections.sort(list);
     -> list.toArray();

    -> Arrays.asList(arr);
    -> list.toArray(new Integer[0]);

# 3) String
    -> s.length()
    -> s.charAt(i)
    -> s.charAt(i) - 'A';char → int index (A-Z)
    -> s.charAt(i) - '0';digit char → int
    -> s.substring(l, r)  // r is EXCLUSIVE
    -> s.indexOf("ab")  s.indexOf('a')
    -> s.contains("abc")
    -> s.startsWith("abc")  s.endsWith("xyz")

# 4) StringBuilder
    -> StringBuilder sb = new StringBuilder();
    -> sb.append('a');
    -> sb.toString();
    -> sb.insert(index, 'x');
    -> sb.deleteCharAt(i);
    -> sb.delete(startIndex, endIndex);  // endIndex is exclusive
    -> sb.replace(start, end, "new");
    -> sb.reverse(); 
    -> sb.charAt(i)
    -> sb.setCharAt(i, 'x');

    -> char[] arr = s.toCharArray();
    -> String str = new String(arr);
    -> String.valueOf(x)
    -> Integer.parseInt(s)
    -> s.equals("abc")
    -> s.equalsIgnoreCase("abc")
    -> s.compareTo("xyz") // lexicographical
    -> s.replace('a', 'b')
    -> s.replace("abc", "x")
    -> s.trim()
    -> s.toUpperCase()
    -> s.toLowerCase()
    -> s.split(" ") ,s.split(",")
    -> String.join(",", list)
    -> Character.isDigit(ch)
    -> Character.isLetter(ch)
    -> Character.toLowerCase(ch)
    -> Character.toUpperCase(ch)
