import java.util.ArrayList;
import java.util.List;

public class ArrayListDemo {
    public static void main(String[] args) {
        // 创建 ArrayList（初始容量10，但可动态增长）
        List<String> list = new ArrayList<>();
        
        // 添加元素
        list.add("Java");
        list.add("Spring Boot");
        list.add("MySQL");
        
        // 随机访问：通过索引直接拿，时间复杂度 O(1)
        String second = list.get(1);  // "Spring Boot"
        
        // 遍历
        for (String item : list) {
            System.out.println(item);
        }
        
        // 在指定位置插入（会导致后续元素后移）
        list.add(1, "MyBatis");
        
        // 删除指定位置（后续元素前移）
        list.remove(2);
        
        System.out.println("最终集合：" + list);
    }
}
