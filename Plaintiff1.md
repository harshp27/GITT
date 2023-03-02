import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class Plaintiff1 {

	public static void main(String[] args) throws InterruptedException {
		System.setProperty("webdriver.chrome.driver","./driver/chromedriver.exe");
		WebDriver driver=new ChromeDriver();		
		driver.get("https://www.accessibility.com/digital-lawsuits");
		
		driver.findElement(By.id("hs-eu-confirmation-button")).click();
		driver.findElement(By.linkText("ANDREW TORO v. Atwood Distributing, L.P.")).click();
		driver.findElement(By.linkText("BRAULIO THORNE v. LIPSCOMB UNIVERSITY")).click();
		driver.findElement(By.linkText("BRAULIO THORNE v. UNIVERSITY OF EVANSVILLE")).click();
		driver.findElement(By.linkText("BRAULIO THORNE v. UNIVERSITY OF MIAMI")).click();
		driver.findElement(By.linkText("JAMES WATSON v. OFFERDAHL'S OFF-THE-GRILL INC.")).click();
		driver.findElement(By.linkText("ANDREW TORO v. Awesome Diecast, LLC")).click();
		
		
		
	}

}