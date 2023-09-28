package entities; // USAMOS ENTITIAS, POIS ELA É UMA ENTIDADE DO MEU NEGOCIO.

public class Product {

	public String name;
	public double price;
	public int quantit;
	
	public double totalValueInStock() {
		return price * quantity;
	}
    
	public void addProducts(int quantity) {
		this.quantity += quantity;
	}
	
	public void public void removerProducts(int quantity) {
		this.quantity -= quantity;
	}
	
	public String toString() {
		return name
				
			+ ", $"
			+ String.format("%.2f", price);
		    +","
		    + quantity
		    +"units Total: $ "
		    +String.format("%.2f", totalValueInStock());
	}
}
""