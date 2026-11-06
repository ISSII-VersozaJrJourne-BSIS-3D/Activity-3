namespace EdrichLogincenter4u
{
    partial class Registerform
    {
        /// <summary>
        /// Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        /// Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            groupBox1 = new GroupBox();
            linkLabel1 = new LinkLabel();
            button1 = new Button();
            label6 = new Label();
            label5 = new Label();
            label4 = new Label();
            label3 = new Label();
            textBox4 = new TextBox();
            textBox3 = new TextBox();
            textBox2 = new TextBox();
            textBox1 = new TextBox();
            label2 = new Label();
            label1 = new Label();
            groupBox1.SuspendLayout();
            SuspendLayout();
            // 
            // groupBox1
            // 
            groupBox1.BackColor = SystemColors.ActiveCaption;
            groupBox1.Controls.Add(linkLabel1);
            groupBox1.Controls.Add(button1);
            groupBox1.Controls.Add(label6);
            groupBox1.Controls.Add(label5);
            groupBox1.Controls.Add(label4);
            groupBox1.Controls.Add(label3);
            groupBox1.Controls.Add(textBox4);
            groupBox1.Controls.Add(textBox3);
            groupBox1.Controls.Add(textBox2);
            groupBox1.Controls.Add(textBox1);
            groupBox1.Controls.Add(label2);
            groupBox1.Controls.Add(label1);
            groupBox1.Location = new Point(29, 26);
            groupBox1.Name = "groupBox1";
            groupBox1.Size = new Size(1119, 769);
            groupBox1.TabIndex = 0;
            groupBox1.TabStop = false;
            groupBox1.Text = "RegisterForm";
            // 
            // linkLabel1
            // 
            linkLabel1.AutoSize = true;
            linkLabel1.Font = new Font("Times New Roman", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            linkLabel1.Location = new Point(446, 669);
            linkLabel1.Name = "linkLabel1";
            linkLabel1.Size = new Size(245, 19);
            linkLabel1.TabIndex = 12;
            linkLabel1.TabStop = true;
            linkLabel1.Text = "Did you have an account? Log in here. ";
            linkLabel1.LinkClicked += linkLabel1_LinkClicked;
            // 
            // button1
            // 
            button1.BackColor = SystemColors.HotTrack;
            button1.BackgroundImageLayout = ImageLayout.Center;
            button1.Font = new Font("Times New Roman", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            button1.ForeColor = SystemColors.ActiveCaptionText;
            button1.Location = new Point(485, 590);
            button1.Name = "button1";
            button1.Size = new Size(154, 52);
            button1.TabIndex = 11;
            button1.Text = "Register";
            button1.UseVisualStyleBackColor = false;
            button1.Click += button1_Click;
            // 
            // label6
            // 
            label6.AutoSize = true;
            label6.Font = new Font("Times New Roman", 14.25F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label6.Location = new Point(603, 427);
            label6.Name = "label6";
            label6.Size = new Size(195, 21);
            label6.TabIndex = 10;
            label6.Text = "Re-enter your Password:";
            // 
            // label5
            // 
            label5.AutoSize = true;
            label5.Font = new Font("Times New Roman", 14.25F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label5.Location = new Point(92, 427);
            label5.Name = "label5";
            label5.Size = new Size(88, 21);
            label5.TabIndex = 9;
            label5.Text = "Password:";
            // 
            // label4
            // 
            label4.AutoSize = true;
            label4.Font = new Font("Times New Roman", 14.25F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label4.Location = new Point(603, 265);
            label4.Name = "label4";
            label4.Size = new Size(88, 21);
            label4.TabIndex = 8;
            label4.Text = "Username:";
            // 
            // label3
            // 
            label3.AutoSize = true;
            label3.Font = new Font("Times New Roman", 14.25F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label3.Location = new Point(90, 265);
            label3.Name = "label3";
            label3.Size = new Size(90, 21);
            label3.TabIndex = 7;
            label3.Text = "Full Name:";
            // 
            // textBox4
            // 
            textBox4.Location = new Point(603, 461);
            textBox4.Multiline = true;
            textBox4.Name = "textBox4";
            textBox4.Size = new Size(435, 54);
            textBox4.TabIndex = 6;
            textBox4.TextChanged += textBox4_TextChanged;
            textBox4.UseSystemPasswordChar = true;
            // 
            // textBox3
            // 
            textBox3.Location = new Point(90, 461);
            textBox3.Multiline = true;
            textBox3.Name = "textBox3";
            textBox3.Size = new Size(435, 54);
            textBox3.TabIndex = 5;
            textBox3.TextChanged += textBox3_TextChanged;
            textBox3.UseSystemPasswordChar = true;
            // 
            // textBox2
            // 
            textBox2.Location = new Point(603, 299);
            textBox2.Multiline = true;
            textBox2.Name = "textBox2";
            textBox2.Size = new Size(435, 54);
            textBox2.TabIndex = 4;
            textBox2.TextChanged += textBox2_TextChanged_1;
            // 
            // textBox1
            // 
            textBox1.Location = new Point(90, 299);
            textBox1.Multiline = true;
            textBox1.Name = "textBox1";
            textBox1.Size = new Size(435, 54);
            textBox1.TabIndex = 3;
            textBox1.TextChanged += textBox1_TextChanged;
            // 
            // label2
            // 
            label2.AutoSize = true;
            label2.Font = new Font("Times New Roman", 15.75F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label2.Location = new Point(458, 114);
            label2.Name = "label2";
            label2.Size = new Size(181, 23);
            label2.TabIndex = 2;
            label2.Text = "Create your Account";
            // 
            // label1
            // 
            label1.AutoSize = true;
            label1.BackColor = Color.FromArgb(192, 255, 255);
            label1.Font = new Font("Times New Roman", 36F, FontStyle.Regular, GraphicsUnit.Point, 0);
            label1.ForeColor = Color.MediumBlue;
            label1.Location = new Point(160, 29);
            label1.Name = "label1";
            label1.Size = new Size(857, 55);
            label1.TabIndex = 1;
            label1.Text = "INVENTORY MANAGEMENT SYSTEM\r\n";
            label1.Click += label1_Click;
            // 
            // Registerform
            // 
            AutoScaleDimensions = new SizeF(7F, 15F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(1182, 817);
            Controls.Add(groupBox1);
            ImeMode = ImeMode.On;
            Name = "Registerform";
            Text = "Registerform";
            groupBox1.ResumeLayout(false);
            groupBox1.PerformLayout();
            ResumeLayout(false);
        }

        #endregion

        private GroupBox groupBox1;
        private Label label1;
        private TextBox textBox1;
        private Label label2;
        private Label label6;
        private Label label5;
        private Label label4;
        private Label label3;
        private TextBox textBox4;
        private TextBox textBox3;
        private TextBox textBox2;
        private Button button1;
        private LinkLabel linkLabel1;
    }
}