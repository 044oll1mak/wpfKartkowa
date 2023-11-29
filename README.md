<Window x:Class="powtorka.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:powtorka"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <DockPanel>
        <Button>1</Button>
        <Button>2</Button>
        <Button>3</Button>
        <Button Width="10" Margin="20">4</Button>
        <Grid>
            <Grid.ColumnDefinitions>
                 <ColumnDefinition />
                 <ColumnDefinition />
                 <ColumnDefinition />
            </Grid.ColumnDefinitions>
            <Grid.RowDefinitions>
                <RowDefinition />
                <RowDefinition />
            </Grid.RowDefinitions>
            <TextBlock FontSize="12" FontWeight="Bold" Grid.Row="0" Grid.Column="0" Grid.ColumnSpan="2">
                <DockPanel Height="200">
                    <Button Margin="5 0">1</Button>
                    <Button Margin="5 0">1</Button>
                    <Button Margin="5 0">1</Button>
                    <Button Margin="5 0">1</Button>
                    <WrapPanel>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                        <Button>1</Button>
                    </WrapPanel>
                </DockPanel>
            </TextBlock>
            <TextBlock FontSize="12" FontWeight="Bold" Grid.Row="0" Grid.Column="2">
                <Grid Width="100" Height="200">
                    <Grid.ColumnDefinitions>
                        <ColumnDefinition/>
                    </Grid.ColumnDefinitions>
                    <Grid.RowDefinitions>
                        <RowDefinition/>
                        <RowDefinition/>
                    </Grid.RowDefinitions>
                    <TextBlock FontSize="12" FontWeight="Bold" Grid.Row="0" Grid.Column="0">
                        <TabPanel Width="200">
                            <Button Width="50" Height="100">1</Button>
                            <Button Width="50" Height="100">1</Button>
                            <Button Width="50" Height="100">1</Button>
                            <Button Width="50" Height="100">1</Button>
                        </TabPanel>
                    </TextBlock>
                    <TextBlock FontSize="12" FontWeight="Bold" Grid.Row="1" Grid.Column="0">
                        <TabPanel Width="200">
                            <Button Width="50" Height="100">1</Button>
                            <Button Width="50" Height="100">1</Button>
                            <Button Width="50" Height="100">1</Button>
                        </TabPanel>
                    </TextBlock>
                </Grid>
            </TextBlock>
            <TextBlock FontSize="12" FontWeight="Bold" Grid.Row="1" Grid.Column="0">
                <Grid Width="100" Height="200">
                    <Grid.ColumnDefinitions>
                        <ColumnDefinition/>
                        <ColumnDefinition/>
                    </Grid.ColumnDefinitions>
                    <Grid.RowDefinitions>
                        <RowDefinition/>
                        <RowDefinition/>
                        <RowDefinition/>
                    </Grid.RowDefinitions>
                    <Button Grid.Row="0" Grid.Column="0">1</Button>
                    <Button Grid.Row="0" Grid.Column="1">1</Button>
                    <Button Grid.Row="1" Grid.Column="0">1</Button>
                    <Button Grid.Row="1" Grid.Column="1">1</Button>
                    <Button Grid.Row="2" Grid.Column="0">1</Button>
                    <Button Grid.Row="2" Grid.Column="1">1</Button>
                </Grid>
            </TextBlock>
            <TextBlock FontSize="12" FontWeight="Bold" Grid.ColumnSpan="2" Grid.Row="1" Grid.Column="1">
                <StackPanel Width="478">
                    <Button>1</Button>
                    <Button>1</Button>
                    <Button>1</Button>
                    <Button>1</Button>
                    <Button>1</Button>
                </StackPanel>
            </TextBlock>
        </Grid>
    </DockPanel>
</Window>
