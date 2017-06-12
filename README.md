# Spss-develop-by-java
could anyone help me out with the problem that how can i develop a java application by using spss interface.if could,I'll could not thanks more.

  try {
	        StatsUtil.start();
	        String[] command={"OMS",
	                "/DESTINATION FORMAT=HTML OUTFILE='/output/demo.html'.",
	                "DATA LIST FREE /salary (F).",
	                "BEGIN DATA",
	                "21450",
	                "30000",
	                "57000",
	                "END DATA.",
	                "DESCRIPTIVES salary.",
	                "OMSEND."};
	       StatsUtil.submit(command);
	       StatsUtil.stop();
	   } catch (StatsException e) {
	       e.printStackTrace();
	   }
why hava i met the problem naming "java.io.IOException: Cannot run program "D:\cllWorkspace\workSpace\SpssDemo\lib/StartXD.exe": CreateProcess error=2"
