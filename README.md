# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `დავალების ინსტურქცია`

## გარემოს მომზადება:

    გარემოს მოსამზადებლად დაგჭირდებათ github-ის ექაუნთი, თუ არ გაქვთ არსებული, მაშინ შექმენით ახალი.

    თქვენი github-ის ექაუნთით გახსენით მოცემული რეპოზიტორია.

    გახსენით ახალი codespace, მეინიდან მოჭერით ახალი ბრენჩი, დაარქვით თქვენი სახელი და გვარი და იმუშავეთ github-ში ჩაინტეგირებულ ide-ში.

    თუ დროზე ადრე მორჩით მუშაობას, დროის ამოწურვამდე არ დაფუშოთ თქვენი ბრენჩი მეინზე.

## დავალების ინსტრუქცია:

მოცემული დავალებების შესასრულებლად გეძლევათ 1-სთ.

დავალება შედგება 2 ნაწილისგან: React და JavaScript ალგორითმები. ალგორითმების ნაწილი მოიცავს ბოუნს ამოცანას, რომელიც არ არის სავალდებულო.

პირველი ნაწილი: React

    1.	Home გვერდზე ბათონზე დაჭერით გააერთიანებთ data ფოლდერში მოცემულ Array_1-ს და Array_2-ს,
    	მიღებული მასივი უნდა იყოს მხოლოდ უნიკალური ელემენტებისგან შემდგარი.
    	არ შეგიძლიათ გამოიყენოთ მეთოდები როგორებიცაა: filter, map, reduce, find, some, any, sort,  და ა.შ.
    	(ამოცანა უნდა დაწეროთ: for ან/და while ციკლების და if/else-ების გამოყენებით)

    2.	მასივების გაერთიანების პროცესის შემდეგ უნდა გადავიდეთ List გვერდზე და დავარენდეროთ მიღებული მასივი.
    	დარენდერებული თითოეული კომპონენტი უნდა შეიცავდეს, "name"-ს, "bodys"-ს და ასევე ფუნქციონირებად წაშლის ღილაკს.

მეორე ნაწილი: Javascriptis ალგორითმები

ალგორითმული ამოცანების საწერად, შეგიძლიათ ნებისმიერ გვერდზე გაიტანოთ ცალკე ფუნქცია და კონსოლის საშუალებით დატესტოთ.

    1.	მოცემული გვაქვს ლუწი ოდენობის რიცხვთა მასივი, მასივში არსებულ ელემენტთა წყვილებს გავუცვალოთ ინდექსები და
    	მიღებული მასივი დავაბრუნოთ სტირნგის სახით.

    	მაგ: [1,2,3,4,2,3] - > [2,1,4,3,3,2] -> "214332"

    2. 	მოცემული გვაქვს დადებითი რიცხვების მასივი, ფუნქციამ უნდა დააბრუნოს მაქსიმალური დადებითი სხვაობა ორ რიცხვს შორის ისე,
    	 რომ საკლების(რიცხვს, რომელსაც აკლდება) ინდექსი მეტი უნდა იყოს მაკლების(რიცხვი, რომელიც აკლდება) ინდექსზე,
    	 დადებითი სხვაობის არ არსებობის შემთხვევაში დააბურნოს 0.

    	მაგ1: [8,2,5,6,1,4] -> პასუხი: 4, ახსნა: 6-2=4, 6-ის ინდექსი მეტია 2-ის ინდექსზე;
    	მაგ2: [12,10,8,5,4] -> პასუხი: 0, ახსნა: არცერთი მარცხნივ მდგომი ელემენტი არ არის ნაკლები მარჯვნივ მდგომზე;
    	მაგ3: [9,35,5,17,1,3] -> პასუხი: 26, ახსნა 35-9=26, 35-ის ინდექსი მეტია 9-ის ინდექსზე;

    3.	(ბონუს ამოცანა) მოცემული გვაქვს ორი სტრინგი, შეგვიძლია თუ არა პირველი სტრინგის წრეზე დატრიალებით მივიღოთ მეორე სტრინგი.
    	abc-ს წრეზე დატრიალებები. abc -> cab -> bca -> abc.

    	მაგ: "abc", "cab" -> true
