# CHCoursel


#import <CHCoursel/CHCoursel.h>
@interface ViewController ()<CHCourselControlViewdelegate>




    CHCourselControlView* courselControlView = [[CHCourselControlView alloc]initWithFrame:CGRectMake(0, 5, self.view.bounds.size.width, 200) imageArr:@[@"1",@"2",@"3"] andSpace:2.5];
    [self.view addSubview:courselControlView];
    courselControlView.delegate = self;
    
    
    
    
    
-(void)CHCourselControlViewTap{
    NSLog(@"tap");
}
