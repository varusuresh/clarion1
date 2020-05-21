# helloworld1
package java8.features;

import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;
import java.util.logging.Logger;

public class DictionaryGeneration {
	private static Logger logger=Logger.getLogger(Logger.GLOBAL_LOGGER_NAME) ;
	public static void main(String[] args) {
		Scanner in=new Scanner(System.in);
		logger.info("Enter Integral Number:");
		int num=in.nextInt();
		List<String> list=new ArrayList<>();
		for(int i=1;i<=num;i++){
			list.add(i+":"+i*i);
		}
		logger.info("Dictionary is:"+list);
	}

}
