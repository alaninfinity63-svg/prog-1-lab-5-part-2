24.HashMap provides all of the optional map operations, and permits null values and the null key.
25.import java.util.HashMap;
     HashMap<String, String> capitalCities = new HashMap<>(){decleration}
  methods
    capitalCities.put("England", "London");
        capitalCities.put("Germany", "Berlin");
        capitalCities.put("Norway", "Oslo");
dependent method get  put 
  26.size ()
  27.
  28. it overwrites the previous key
  29.both entries are stored indepedently
  30.if (map.containsKey("Cameroon")) {
    System.out.println("Key exists!");
}
 31.returns null
 32.for (String key : map.keySet()) {
    System.out.println(key);
}
 33