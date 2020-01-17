fn main() {
    assign7q1::sub_mod::hello();
}
pub mod assign7q1{
    pub mod sub_mod {
        pub fn hello() {
            println!("Hello from sub module 1");
        }
    }
}
